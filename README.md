# Abbor

A simple CBOR analyzer, named after the European Perch, which is called "Abbor" in Norwegian.

## Example usage

```
cargo run suit_envelope_with_cose
```

*Note:* Abbor expects the input file to have hex-formatted CBOR.
That is, it will choke on CBOR binary files.
The reason for this is simple: Abbor was developed to interpret CBOR from IETF RFCs and drafts,
and those guys use ASCII art for everything.
