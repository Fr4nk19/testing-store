<p align="center">
  <img src="https://dango.digital/images/logo-violeta.png" width="174" alt="Dango Digital" />
</p>

<h1 align="center">
  PROJECT NAME, Shopify store development.
</h1>

<div align="center">

[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen)](https://github.com/Dango-Team/REPO_NAME/tree/documentation/readme)
[![Join us @nrwl/community on slack](https://img.shields.io/badge/slack-dango_digital-brightgreen?logo=slack)](https://dango-digital.slack.com/)
[![Shopify Store](https://img.shields.io/badge/shopify-store--dev-brightgreen?logo=shopify)](https://STORE_URL.myshopify.com/admin)

</div>

<hr>

## Requirements 

- Themekit
- A computer (if possible)


## Important 

Be sure that you make a copy of config.yml.dist, rename it to config.yml and setup your password and theme id.

```yaml
development:
  password: xxxx
  theme_id: xxxx
  store: store-name.myshopify.com
  ignore_files:
    - config/settings_data.json
    - config/settings_schema.json
```

## Contributing

- Single-purpose commits
- Meaningful commit messages
- Labeled pull requests
- Branch frequently
- Follow branch convention naming

```yaml
bugfixes/{the-task}
hotfix/{the-task}
documentation/{the-task}
enhancement/{the-task}
feature/{the-task}
development/{the-task}
```
