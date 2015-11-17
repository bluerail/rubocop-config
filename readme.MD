Bluerail Rubocop config
=======================

Usage
=====

Add a .rubycop.yml in your project root with content

```yaml
inherit_from:
  - https://raw.githubusercontent.com/bluerail/rubocop-config/master/rubocop.yml
```

And in your .gitignore:

```
.rubocop-https*yml
```

Requirements
============

inherit_from was added in Rubocop 0.35.0 so that's the minimum required version
