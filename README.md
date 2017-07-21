# pcdns
A sample DNS for Parental Control

This is a sample implementation to use DNS to return blocked or malicious websites for the purpose of **Parental Control**. It uses the [DNS library in Go](https://github.com/miekg/dns), and return the EDNS0 record per the query.
