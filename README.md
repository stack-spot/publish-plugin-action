# publish-plugin-action

[![Action test](https://github.com/stack-spot/publish-plugin-action/actions/workflows/action-test.yml/badge.svg)](https://github.com/stack-spot/publish-plugin-action/actions/workflows/action-test.yml)

GitHub action to publish plugin

## 📚 Usage

### Requirements

To get the account keys (`CLIENT_ID`, `CLIENT_KEY` and `REALM`), please login using a **ADMIN** user on the [StackSpot Portal](https://stackspot.com), and generate new keys at [https://stackspot.com/en/settings/access-token](https://stackspot.com/en/settings/access-token).

### Use Case

```yaml
    steps:
      - uses: stack-spot/publish-plugin-action@v1.0
        with:
          client_id: ${{ secrets.CLIENT_ID }}
          client_key: ${{ secrets.CLIENT_KEY }}
          realm: ${{ secrets.REALM }}

```

## License

[Apache License 2.0](https://github.com/stack-spot/publish-plugin-action/blob/main/LICENSE)
