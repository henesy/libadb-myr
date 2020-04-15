# libadb ­ Myrddin

A library

## Build

	mbld

## Test

	mbld test

## Install

	mbld install

## The Attrdb file format

Rules:

- Whitespace is sensitive
- The first rune of the line is significant
- Leading `#` is a comment
- An `attribute=value` pair must have no whitespace
- Whitespace in a value must be quoted with `'`
- A literal `'` may be inserted as per `''`
- An empty value can be represented as per `attribute=`
- Leading whitespace is a further set of attributes for a parent
- Attributes on the same line bind tighter than separate lines

## References

- http://man.postnix.pw/inferno-oS/2/attrdb
- http://man.postnix.pw/inferno-oS/2/cfg
