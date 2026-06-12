# LegacyFixer dependency hell test

Controlled repository for validating LegacyFixer behavior when dependency resolution is impossible.

Expected conflict:

- requests==2.19.1 requires urllib3 >=1.21.1,<1.24
- requirements.txt pins urllib3==2.0.0
