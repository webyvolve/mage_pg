## 🤔 What is it?

This is a Docker Compose template for running mage.ai with postgres as a backend. Postgres is used for storing logs and secrets.

## 🙋‍♂️ Why did you create it?

This compose template is intended to be used for lightweight batch data integration tasks. The mage container has had root access removed.

## Setup Steps:

1. Consider updating the postgres credentials since in the .env file since they are default values.
2. Update network settings for services mage and postgres if not working locally.
