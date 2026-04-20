# PES-VCS (OS Orange Problem)

## Student Details
Name: Prithvi Raj Pandey  
USN: PES1UG25CS833  

## Objective
To implement a simple version control system using operating system concepts like file handling, hashing, and indexing.

## Features
- Object storage using SHA-256
- Tree creation
- Index (staging area)
- Commit and log system

## How to Run

```bash
make
./pes init
echo "hello world" > file.txt
./pes add file.txt
./pes commit -m "first commit"
./pes log
