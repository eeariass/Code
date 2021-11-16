#!my @scripts;

You can check how to execute them with '-h' or '--help' options as:
<script_name> -h || <script_name> --help

```
./asn - return company name given a BGP ASN number;
./rpki-invalids - return list of IPv4/v6 RPKI INVALID prefixes given BGP ASN number;
./bgptotals - return total internet IPv4/v6 route count;
./roa - return whether the given IP has ROA or not;
./prefix-origin - return ASN where the BGP prefix is being originated from;
./vrp - return VRPs from ASN;
```

```
Special thanks {
  bgpstuff.net for having the site up and running for us to query;
}
```
