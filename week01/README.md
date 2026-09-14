Hello World
# Week 01 Assignment

## AI-Ready Code Editor

I chose Visual Studio Code as my AI-ready code editor.

### Code used

```bash
which code
code --version
```

## Samtools Version

### Code used

```bash
samtools --version
```

### Output

```text
samtools 1.24
Using htslib 1.24
Copyright (C) 2026 Genome Research Ltd.
```

The version of `samtools` in my `bioinfo` environment is **1.24**.

## Creating Nested Directories

### Code used

```bash
mkdir -p data/raw/sequences
find data -type d
```

### Output

```text
data
data/raw
data/raw/sequences
```

## Creating Files in Different Directories

### Code used

```bash
touch data/notes.txt
touch data/raw/samples.txt
touch data/raw/sequences/example.fasta
find data -type f
```

### Output

```text
data/notes.txt
data/raw/sequences/example.fasta
data/raw/samples.txt
```

## Relative and Absolute Paths

### Relative Path

A relative path specifies the location of a file relative to the current working directory.

#### Code used

```bash
cat data/notes.txt
```

#### Output

```text
Week 01 notes
```

### Absolute Path

An absolute path specifies the complete location of a file starting from the root directory.

#### Code used

```bash
cat /home/susel/appbio-2026/week01/data/notes.txt
```

#### Output

```text
Week 01 notes
```

