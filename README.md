# pbcat 📡

## Overview 

`pbcat` outputs null terminated PocketBase Records to the standard output.

## Build

To build `pbcat`, run the following command:

```bash
go mod download
go build -o pbcat/main pbcat/main.go
```

## Usage

To start listening to your PocketBase records, use the following command:

```bash
main --record <recordName> 
```

Replace `<recordName>` with the name of the record you want to monitor (eg `Users`)
