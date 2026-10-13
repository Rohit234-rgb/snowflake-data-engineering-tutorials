# Snowflake Table Types Explained (Time Travel, Fail-safe & Cost)

Learn how Snowflake Table Types Explained (Time Travel, Fail-safe & Cost).

## 🎥 Watch the YouTube Short

[Watch the video on YouTube]((https://youtu.be/Y4tgv3lN-tM))

## 📚 Topics Covered
Snowflake has several table types, and the one you pick changes how safe your data is and how much you pay. This video explains each one simply, with animations: permanent, transient, temporary, external, dynamic and Iceberg tables, plus Time Travel, Fail-safe and cost.

Quick answers:
- Permanent: durable data, with Time Travel and Fail-safe.
- Transient: limited Time Travel (0 or 1 day), no Fail-safe.
- Temporary: lasts only for the session, no Fail-safe.
- Fail-safe: a last resort handled by Snowflake Support. You cannot query it.

Important: Time Travel retention limits depend on the table type, your Snowflake edition and your settings. Dynamic and Iceberg table behavior also depends on configuration. Always check the latest Snowflake documentation before making production decisions.

## 👨‍💻 About This Repository

This repository shares my learning journey in Snowflake, SQL, Python, dbt, and Data Engineering.
