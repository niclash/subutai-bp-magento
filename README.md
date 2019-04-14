# Magento blueprint

Magento is an eCommerce platform which gives you the power to create unique, limitless, and engaging shopping experiences while offering the security, performance, and low TCO benefits of cloud services. Enjoy rich, out-of-the-box features, an unlimited ability to customize, and seamless third-party integrations. With Magento Commerce, you’re supported by a global ecosystem of merchants, partners, and developers who will bring your commerce vision to life. It’s time to innovate, scale, and achieve extraordinary growth for your small, medium or enterprise business. More https://magento.com

This blueprint installs Magento on Subutai P2P Cloud, learn more about Subutai here https://subutai.io

## Installation guide

1. Fill all variables
- `magentoAdmin` - admin username
- `environmentName` - name of your environment in Subutai Bazaar
- `domainName` - your domain name
- `webContanerName` - Subutai container hostname
- `LeaveAnsibleContainer` - container to deploy application
- `containerSize` - container size type
- `magentoAdminpwd` - admin username password 
- `magentodbUserpwd` - mysql magento username password
- `magentoVersion` - Magento version, take version from here https://github.com/magento/magento2/releases

![Screenshot from 2019-04-14 16-07-50](https://user-images.githubusercontent.com/33412152/56091389-247ea980-5ed0-11e9-8e16-9169ccd1003b.png)

2. Choose peer where your blueprint will be installed
![Screenshot from 2019-04-14 15-09-42](https://user-images.githubusercontent.com/33412152/56090912-12017180-5eca-11e9-893d-7f7977e439c0.png)

3. Press `Finish` 
![Screenshot from 2019-04-14 15-10-02](https://user-images.githubusercontent.com/33412152/56090916-17f75280-5eca-11e9-9559-4670623cd3d2.png)


Wait till the application will be installed be ready
After you can open application by your domain name address you will see your environment frontend page

![Screenshot from 2019-04-08 14-13-32](https://user-images.githubusercontent.com/33412152/56091402-54c64800-5ed0-11e9-812f-b31249218d0c.png)
