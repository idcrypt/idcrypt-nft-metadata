# idcrypt-nft-metadata

This repository hosts the open, transparent, and decentralized metadata used to mint and represent article-based NFTs from the [idcrypt.xyz](https://www.idcrypt.xyz) publication.

Each article minted as an NFT on the Solana blockchain—using the ARDION token—refers to one metadata file hosted in this repository. This ensures full auditability and independence of content indexing, accessible to the public.

---

## 📦 Directory Structure

---

## 📄 Metadata Format

All article NFTs follow a standardized JSON format:

```json
{
  "name": "NFT: Article Title",
  "description": "Short summary of the article content.",
  "external_url": "https://www.idcrypt.xyz/yyyy/mm/article-slug.html",
  "image": "https://raw.githubusercontent.com/idcrypt/idcrypt-nft-metadata/main/covers/xxxx.jpg",
  "attributes": [
    { "trait_type": "Published", "value": "YYYY-MM-DD" },
    { "trait_type": "Category", "value": "Topic or Theme" },
    { "trait_type": "Author", "value": "binka" },
    { "trait_type": "Token", "value": "ARDION" },
    { "trait_type": "NFT Price", "value": "250000 ARD" }
  ]
}

🧪 Metadata Validation
To validate any metadata file, refer to the JSON Schema located at:
schema/metadata-schema.json

👤 Ownership & Contribution
All content is authored, owned, and governed by the developer of the Ardion token and ecosystem (@binka).

At this stage, external contributions are restricted, but future collaboration will be opened for:

Community-published articles

Third-party NFT listings based on ecological or scientific topics
