# Contribution Guidelines

*Türkçe özet aşağıdadır.*

Thanks for helping make this list better. The goal is a small, accurate list of sources that developers can actually use, not the longest list.

## What belongs here

- Open data portals, public APIs, datasets and data-related tools about Türkiye.
- Official sources are preferred. Community projects are welcome when they are maintained, documented and openly licensed.
- Each entry must be useful to developers: downloadable data, an API, a documented data format or a library.

## What does not belong here

- Dead links, parked domains, "coming soon" pages or sites that only show a login wall.
- Services that look up personal data about individuals (identity, address, phone or plate lookups).
- Leaked, scraped-without-permission or otherwise unlawfully obtained datasets.
- Tools whose main purpose is scraping a site against its terms of use.
- Paid products without a meaningful free tier, unless they are the official source (state this clearly).
- Official logos or anything that suggests endorsement by an institution.

## Entry format

```markdown
- [Name](https://example.gov.tr/) - Short English description. Access notes. *Kısa Türkçe açıklama.*
```

- Use the official name of the source as the link text.
- Link to the most specific stable page (for example the API documentation or dataset page), not a search result.
- The English description starts with a capital letter, does not repeat the name and ends with a full stop.
- Add access notes when relevant: `API key required`, `Free account required`, `Rate limited`, `Web interface only`, `No documented public API`.
- For code, models and datasets, state the license (for example `MIT.` or `CC BY-SA 4.0.`). Non-commercial or custom licenses must be called out.
- Finish with a short Turkish description in italics.
- Add new entries to the end of the relevant section, or open an issue if you think a new section is needed.

## Before you open a pull request

1. Open the link yourself and confirm it is live and shows the content you describe.
2. Search the list to make sure the source is not already included.
3. Keep one source per pull request when possible, and explain in the pull request why it is useful.
4. Make sure the checks pass. Every pull request runs [awesome-lint](https://github.com/sindresorhus/awesome-lint) and the [lychee](https://github.com/lycheeverse/lychee) link checker. You can run the linter locally with `npx awesome-lint`.

Some Turkish public sites block requests from outside Türkiye or from automated clients. If the link checker fails only because of such blocking, mention it in the pull request so the host can be added to `.lycheeignore` after a manual check.

## Removing or updating entries

Links break and services change. If you find a dead link, a changed URL, a new key requirement or a license change, please open an issue or send a fix.

---

## Türkçe özet

- Yalnızca canlı, geliştiriciye gerçekten faydalı kaynaklar eklenir; resmî kaynaklar önceliklidir.
- Kişisel veri sorgulama hizmetleri, sızdırılmış veri setleri ve kullanım koşullarına aykırı kazıma araçları eklenmez.
- Biçim: `- [Ad](bağlantı) - İngilizce kısa açıklama. Erişim notları. *Kısa Türkçe açıklama.*`
- Kod, model ve veri setlerinde lisans belirtilmelidir; ticari olmayan veya özel lisanslar açıkça yazılmalıdır.
- Çekme isteği göndermeden önce bağlantıyı kendiniz açıp içeriği doğrulayın ve otomatik kontrollerin geçtiğinden emin olun.
- Bozuk bağlantı veya değişen koşullar için konu (issue) açabilir ya da düzeltme gönderebilirsiniz.
