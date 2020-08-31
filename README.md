Rebar3 shell injection (CVE-2020-13802)
=====

## Proof of concept

    git clone https://github.com/vulnbe/poc-rebar3.git
    cd poc-rebar3
    rebar3 clean

## Credit

Alexey Pronin ([@vulnbe](https://twitter.com/vulnbe))

## References

* [Rebar3 vulnerability analysis](https://vuln.be/post/rebar3-command-injection/)
* [Vulnerability remediation PR](https://github.com/erlang/rebar3/pull/2302)
* [CVE-2020-13802](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-13802)
* [CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')](https://cwe.mitre.org/data/definitions/78.html)
