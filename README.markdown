# Veewee Definitions
### Maintainer: [Mark Stanislav](mailto: mark.stanislav@gmail.com "E-Mail Mark Stanislav") ###
### Repository: [https://github.com/mstanislav/Veewee-Definitions](https://github.com/mstanislav/Veewee-Definitions "Mark Stanislav's Veewee Definitions Repository") ###
- - -
## Definitions Available ##
### CentOS-6_x86_64-PuppetStack ###
**Description:** Provides a fully-functional CentOS 6 based 2.7.x Puppet master stack with mCollective 1.3.x + many plugins, The Foreman, RabbitMQ 2.5.x, Apache + Passenger. Easily configurable with variables set at the top of the postinstall.sh to customize many facets of the deployment.

## To Use ##
Follow similar instructions for your path to the template and Ruby gem location:
*   ln -s /Users/mstanislav/github/Veewee-Definitions/CentOS-6_x86_64-PuppetStack /usr/lib/ruby/user-gems/1.8/gems/veewee-0.2.0/templates/
*   vagrant basebox define 'CentOS6-x86_64-PuppetStack' 'CentOS-6_x86_64-PuppetStack'
*   vagrant basebox build 'CentOS6-x86_64-PuppetStack'
