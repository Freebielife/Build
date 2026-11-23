# BUILD Observatory

## О проекте / токене

В метаданных этого контракта BUILD описан как utility-токен для набора инструментов Telegram.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-23):

- <https://tonapi.io/v2/jettons/EQBYnUrIlwBrWqp_rl-VxeSBvTR2VmTfC4ManQ657n_BUILD>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Данные собираются из TonAPI и GeckoTerminal; их полнота и время проверки указаны в снимке и интерфейсе.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Параметры BUILD

- Контракт: `EQBYnUrIlwBrWqp_rl-VxeSBvTR2VmTfC4ManQ657n_BUILD`
- Сайт, связанный в метаданных: https://openbuilders.xyz/
- Канал, указанный владельцем обсерватории: https://t.me/builders
- Логотип: метаданные токена; https://cdn.joincommunity.xyz/build/build_logo.png
- Флаг разделов: TONecoFlags №037, выбран пользователем.
- Общие метки: OG, Fragment +888, четырёхзначные .ton, сжигания.
- Планировщик Cloudflare: подключение и плановый запуск ещё не подтверждены.
