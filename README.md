# Ansible Role: telegram

Notify by Telegram on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    telegram_token: 'botXXXXXXXXX:YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY'
    telegram_chat_id: 'ZZZZZZZZZ'
    telegram_enabled: 'no'
    telegram_message: ''

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - Akman.telegram

*Inside `vars/main.yml`*:

    telegram_token: 'bot123456789:ABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'
    telegram_chat_id: '123456789'
    telegram_enabled: 'yes'
    telegram_message: 'Ok'

## License

MIT / BSD

## Author Information

This role was created in 2017 by Alexander Kapitman
