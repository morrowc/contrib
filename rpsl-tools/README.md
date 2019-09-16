# RPSL Tools - An example use of the rpsl-parser library.

RPSL-Tools/main.go loads a list of IRR data files, and has
rpsl-parser parse the file into a stream of protobuf results.

Items to improve this, and make it useful include:
  * Collect the results, index them to be queried for
    prefix-list creation
  * Store the indexed data in a persistent data store
  * Provide an interface to request per-asn prefix-list
    creation.
