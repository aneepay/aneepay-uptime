# AneePay Uptime

Open-source uptime monitor and status page for ANeePay services, powered by [Upptime](https://upptime.js.org) and GitHub Actions.

## Monitored Services

| Service     | URL                     |
| ----------- | ----------------------- |
| ANeePay API | https://api.aneepay.com |
| ANeePay     | https://aneepay.com     |

## How it works

- **GitHub Actions** checks availability every 5 minutes
- **Response time** is recorded and committed to git
- **GitHub Issues** are auto-opened when downtime is detected
- **Status page** is deployed to GitHub Pages

## Status Page

Visit: https://status.aneepay.com (or https://aneepay.github.io/aneepay-uptime/)

## Configuration

All settings are in `.upptimerc.yml`. To add new sites, append to the `sites` list:

```yaml
sites:
  - name: My Service
    url: https://my-service.com
```

## Documentation

- [Upptime Docs](https://upptime.js.org/docs)
- [Configuration](https://upptime.js.org/docs/configuration)
- [Notifications](https://upptime.js.org/docs/notifications)

## License

- Code: [MIT](./LICENSE)
- Data: [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)
