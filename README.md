# Address Book

Using Protocol Buffers to implement a simple Address Book command-line application that can read and write people’s contact details to and from a file. Following the [protobuf.dev tutorial](https://protobuf.dev/getting-started/gotutorial/)

see the definition of the address book protocol buffer in [address_book.proto](address_book.proto).

## Usage

### Add a person

```bash
go run cmd/add_person <data_file>
```

### List people

```bash
go run cmd/list_people <data_file>
```
