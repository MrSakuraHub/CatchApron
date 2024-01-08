# License

This `Security.md` file is licensed both with:

- MIT license, by creator of this document Lauri Ojansivu https://github.com/xet7
- AGPL-3.0 license, original at this repo

# Confidential Computing

- https://twit.tv/shows/floss-weekly/episodes/731?autostart=false
- https://github.com/confidential-computing
- https://confidentialcomputing.io/wp-content/uploads/sites/10/2023/03/CCC_Overview.pdf
- https://github.com/CCC-Attestation/meetings

## Azure

Only customer has decyption keys. Azure admins do not have any access to server where disk and RAM is fully encrypted. VM has Ubuntu or Windows.

2022-07-2022: "We are excited to announce the general availability of Azure DCasv5 and ECasv5
confidential VM-series utilizing 3rd Gen AMD EPYC (TM) processors with
Secure Encrypted Virtualization-Secure Nested Paging (SEV-SNP) security features."

- https://techcommunity.microsoft.com/t5/azure-confidential-computing/azure-confidential-vms-dcasv5-ecasv5-using-amd-sev-snp/ba-p/2993530
- https://github.com/microsoft/ccf-app-samples/blob/main/banking-app/README.md
- https://github.com/microsoft/ccf-app-samples
- https://github.com/microsoft/CCF
- https://www.microsoft.com/en-us/research/project/confidential-consortium-framework/
- https://learn.microsoft.com/en-gb/azure/confidential-computing/confidential-vm-overview
- https://learn.microsoft.com/en-gb/azure/confidential-computing/application-development
- https://learn.microsoft.com/en-gb/azure/confidential-computing/confidential-vm-faq

## Enclaves

- https://github.com/openenclave/openenclave
- https://www.edgeless.systems/products/ego/
- https://learn.microsoft.com/en-gb/azure/confidential-computing/enclave-development-oss

# Programming Language Security

## C89

- Writing Security Software: CCC talk about dropping privileges, only allowing append files (not modify previous), CGI scripts with C89, etc https://www.youtube.com/watch?v=TaE28fJVPTk

## Ada

- https://en.wikipedia.org/wiki/Ada_(programming_language)
- https://ada-lang.io
- Coding with ADA https://www.adacore.com/uploads/techPapers/222559-adacore-nvidia-case-study-v5.pdf
- Writing crash proof software https://www.cambridge.org/core/books/building-high-integrity-applications-with-spark/F213D9867D2E271F5FF3EDA765D48E95

## Tcl

- Safe-Tcl Sandbox https://www.tcl.tk/software/plugin/safetcl.html

## Javascript

- Deno can disable dependencies access to filesystem, network etc https://deno.com 

## Rust

- MIT: Rust Web framework https://rust-on-nails.com https://github.com/purton-tech/rust-on-nails

# Database Security

- Encrypted SQLite GUI https://github.com/yyamasak/TkSQLite-Cipher
- MIT: GDPR WebUI and API to SQLite/PostgreSQL etc https://databunker.org https://github.com/securitybunker/databunker#readme
- Apache2 License: Streaming backup of SQLite https://litestream.io https://github.com/benbjohnson/litestream

# Webserver Security

- Apache2 License: Caddy's TLS defaults are secure and pass PCI, HIPAA, and NIST compliance requirements https://caddyserver.com https://github.com/caddyserver/caddy
- ProtonMail web and mobile clients, some encryption and email code https://github.com/ProtonMail
- AGPLv3: Collaborative office suite, end-to-end encrypted https://cryptpad.org https://github.com/cryptpad/cryptpad

# Other web frameworks, not security related

- MIT: Serverless Web Framework https://hono.dev

# ONTOCHAIN

- GPLv3: https://github.com/ONTOCHAIN/POC4COMMERCE
- https://github.com/ONTOCHAIN

# Progressive enhancement, graceful degradation

- https://unpoly.com , so that webpage also works without Javascript. For this use, better than HTMX https://www.youtube.com/watch?v=d0LwUqb9e_k
