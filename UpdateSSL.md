# How to Update Your SSL Certificate
An SSL certificate is what adds an extra layer of security to your site. If you have ever noticed "https://" compared to a "http://". 
The "s" means that there is a SSL certificate attached to this site. It's basically an encrypted connection between your computer and the site.

##### The SSL certificate provider we used was called [Lets Encrypt](https://letsencrypt.org/)

- Log onto the [server console](https://aws.amazon.com/console/)
    + *NOTE:* You will have to use Two Factor Authentication to log in
- Launch the server to open a Bitnami window

![bitnami info](https://github.com/rgooney/WillowsfordArcheryTraining/blob/main/imgs/bitnami.PNG)

- Follow the steps that [bitnami](https://docs.bitnami.com/aws/how-to/generate-install-lets-encrypt-ssl/#step-5-renew-the-lets-encrypt-certificate) provides

## Resources for Troubleshooting Errors
Troubleshooting is just **_Googling with style_**.
- Always Google the error, most likely someone has posted on StackOverflow and people far smarter than GMU seniors responded
- Useful Links for Lightsail, Bitnami, and Apache
    + [AWS Lightsail FAQ](https://aws.amazon.com/lightsail/faq/?trk=56417dfe-8849-4622-bfa4-7ec30bd6f5a3&sc_channel=ps&sc_campaign=acquisition&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Compute|Lightsail|US|EN|Text&s_kwcid=AL!4422!3!488982705783!p!!g!!aws%20lightsail&ef_id=CjwKCAjw6dmSBhBkEiwA_W-EoBr7HV-pqSJKiKB7VUmvlvjwmOPWZAYOTsxDOZDKKI2fU9LbjDLzKhoCnsAQAvD_BwE:G:s&s_kwcid=AL!4422!3!488982705783!p!!g!!aws%20lightsail)
    + [Bitnami Troublshooting](https://docs.bitnami.com/aws/how-to/understand-bncert/)
    + [Bitnami SSL Troubleshooting](https://docs.bitnami.com/aws/how-to/troubleshoot-ssl-issues/)
    + [Bitnami for Apache Documentation](https://docs.bitnami.com/aws/apps/wordpress/administration/)

