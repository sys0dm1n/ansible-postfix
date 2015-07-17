# ansible-postfix
Installing Postfix using ANSIBLE with no prompts

Ansible Playbook to quick install POSTFIX on your Ubuntu/Debian servers with no prompt.

Postfix is a free and open-source mail transfer agent (MTA) that routes and delivers electronic mail, intended as an alternative to the widely used Sendmail MTA.


Requirements
------------
ANSIBLE pre installed.

Executing the script:
----------------------
Edit the postfix-install.yml file and replace terraltech.com by your server's inventory name.

    #  ansible-playbook -k postfix-install.yml

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
