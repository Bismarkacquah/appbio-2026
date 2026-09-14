Hello World
# Week 01 Assignment

## AI-ready code editor

I selected Visual Studio Code as my AI-ready editor for bioinformatics work.

### Command used

```bash
which code
code --version
```

## Samtools version

### Command used

```bash
samtools --version
```

### Output

```text
samtools 1.24
Using htslib 1.24
Copyright (C) 2026 Genome Research Ltd.
```

The version of `samtools` in the course `bioinfo` environment is **1.24**.

## Creating nested directories

### Command used

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

## Creating files in different directories

### Command used

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

## Relative and absolute paths

### Relative path

A relative path specifies a file location relative to the current working directory.

#### Command used

```bash
cat data/notes.txt
```

#### Output

```text
Week 01 notes
```

### Absolute path

An absolute path specifies the full file location starting from the filesystem root.

#### Command used

```bash
cat /home/susel/appbio-2026/week01/data/notes.txt
```

#### Output

```text
Week 01 notes
```

