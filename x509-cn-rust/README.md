# x509-rust subject name

Command line rust project that takes a pem file, parses subject name, and validates host through DNS, and returns all IPs it resolves to.

Note: My type and error handling are very amateur at that moment, and there are no unit tests

## Usage 

`cargo run [pem file]`
