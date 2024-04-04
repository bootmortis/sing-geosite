# IR sing-geosite

Used in https://github.com/bootmortis/iran-hosted-domains


## Categories
- `ir`: handpicked `.ir` domains, use as `direct`.
- `other`: non `.ir` domains, use as `direct`.
- `tld-ir`: all `.ir` domains, use as `direct`.
- `all`: a combination of `other` and `tld-ir`, should be used as `direct`.
- `ads`: Iran-related advertising services that need to be `blocked`.
- `proxy`: Iran-related domains that are blocked inside of iran and need to be `proxied`.

## Usage

For more info check [here](https://github.com/bootmortis/iran-hosted-domains?tab=readme-ov-file#sing-box).

### Geosite
`https://github.com/bootmortis/iran-hosted-domains/releases/latest/download/iran-geosite.db`

### Rule-set (v1.8 and later)
`https://github.com/bootmortis/sing-geosite/releases/latest/download/geosite-<category>.srs`  
  
replace `<category>` with the category name. example URL:  

`https://github.com/bootmortis/sing-geosite/releases/latest/download/geosite-ir.srs`  

## Documents
- [How to use geosite](https://github.com/bootmortis/iran-hosted-domains?tab=readme-ov-file#sing-box)
- [Migrate Geosite to rule sets (v1.8)](https://sing-box.sagernet.org/migration/#migrate-geosite-to-rule-sets)
