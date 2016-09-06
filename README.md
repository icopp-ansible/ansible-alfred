# ansible-alfred

Install Alfred via Homebrew Cask.

Note that Alfred is available in the Mac App Store, but is not offered as an option here because that version is extremely out of date (circa 2012).

## Dependencies

* [icopp.homebrew-cask](https://github.com/icopp/ansible-homebrew-cask)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.alfred
```

## License

MIT
