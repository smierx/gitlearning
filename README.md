#!/bin/bash

datei="README.md"

timestamp=$(date '+%Y-%m-%d %H:%M:%S')

echo "$timestamp" >> "$datei"
