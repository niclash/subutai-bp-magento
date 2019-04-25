# Magento blueprint

Magento is an eCommerce platform which gives you the power to create unique, 
limitless, and engaging shopping experiences while offering the security, 
performance, and low TCO benefits of cloud services. Enjoy rich, out-of-the-box
features, an unlimited ability to customize, and seamless third-party 
integrations. With Magento Commerce, you’re supported by a global ecosystem of
merchants, partners, and developers who will bring your commerce vision to life.
It’s time to innovate, scale, and achieve extraordinary growth for your small,
medium or enterprise business. More https://magento.com

This blueprint installs Magento on Subutai P2P Cloud, learn more about Subutai 
here https://subutai.io

## Installation guide

1. Fill all variables
- `magentoAdmin` - Admininistrator's username
- `magentoAdminpwd` - admin username password for the backend, as well as the MySQL server. 
- `environmentName` - name of the Magento environment in Subutai. 
- `domainName` - your domain name
- `containerSize` - container size type, medium is typically enough. If heavy traffic is expected, 
a larger container may help.
- `LeaveAnsibleContainer` - The container that runs the Ansible script. If ticking this box, that
container will remain on the host. Typically, don't need that.

The Magento backend will be available at https://<domainName>/admin