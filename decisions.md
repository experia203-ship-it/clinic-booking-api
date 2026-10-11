## adr-001:postgres as the only database

- decision:will use postgres as the only and mai database.
- alternative-considered:h2 database.
- why: because postgres would be the one in production and we don't want tests to differ if using another database like h2 which behaves differently.