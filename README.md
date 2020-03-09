# ISCN Specifications
International Standard Content Number (ISCN) is designed as a general digital content registry, and it assigns a unique identifier to digital content. Additionally, it registers the content fingerprint, besides, the creation footprint and the distribution footprint, allowing for content attribution, tracking of content distribution or even the content monetization.

## ISCN Schema
The ISCN registry should provide a schema of structured data to describe the digital content, and the goal is to register the following metadata of digital content:

- A globally unique identifier to identify a digital content
- The fingerprint of the digital content
- Stakeholders (such as author, publisher) of the digital content
- The license to the digital content
- The location of the digital content if it is open to public
- The history of the evolution of digital content and the metadata
- The metadata of the digital content

The schema combines a few sections of metadata, and each section has its specifications, the following is the architecture of an ISCN schema:

```
    ISCN metadata
      ├--> Stakeholder
      ├--> License
      └--> Content metadata
```

### ISCN metadata
TBD

### Stakeholder
TBD

### License
TBD

### Content metadata
TBD

## Contributing & Discussion
Suggestions, contributions, criticisms are welcome.

Discussion of specifications happens in [this repository's issues](https://github.com/likecoin/iscn-specs/issues) or via pull request.

Discussion of ISCN more generally happens in the repository [iscn-ipld](https://github.com/likecoin/iscn-ipld/issues).

## License
This repository is only for documents. All of these are licensed under the CC-BY-SA 4.0 license, © 2020 LikeCoin Foundation Ltd.
