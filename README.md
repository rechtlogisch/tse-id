![Recht logisch TSE-ID banner image](rechtlogisch-tse-id-banner.png)

[![Retrieve workflow](https://github.com/rechtlogisch/tse-id/actions/workflows/retrieve.yml/badge.svg?branch=main)](https://github.com/rechtlogisch/tse-id/actions/workflows/retrieve.yml)

# tse-id

> A list of BSI certified technical security devices for electronic recording systems in Germany (BSI-Zertifizierungs-ID für TSE)

Contains the [current list](list/current.json) of TSE-IDs in JSON. It stores the historic [lists](list/) in dated files.

The [BSI webpage](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Zertifizierung-und-Anerkennung/Listen/Zertifizierte-Produkte-nach-TR/Technische_Sicherheitseinrichtungen/TSE_node.html?gts=913608_list%253DdateOfRevision_dt%252Bdesc&gtp=913608_list%253D1) is checked automatically every day at [5 AM UTC and 5 PM UTC](.github/workflows/retrieve.yml#L5) with the [retrieve.yml](.github/workflows/retrieve.yml) workflow.

> [!NOTE]  
> The workflow utlizes the [tse-id-php](https://github.com/rechtlogisch/tse-id-php) package.

## Credits

- [Krzysztof Tomasz Zembrowski](https://github.com/zembrowski)
- [All Contributors](../../contributors)

## Disclaimer

All trademarks, service marks, trade names, product names appearing within the [lists](list/) are the property of their respective owners. Any rights not expressly granted herein are reserved. The use of any trademark without the express written consent of the trademark owner is strictly prohibited.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
