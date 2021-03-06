# FullBellies

FullBellies is an application that connects restuaurants and grocers directly with customers, allowing vendors to sell leftover and soon to be expired foods that might otherwise be thrown out and accounted for as a loss.  This application was built with the intention of cutting down on overall food waste, while also making affordable meals more accessaible.

##Members
#### [Lowell Mower](https://github.com/lowellmower)
#### [Marc Cardacci](https://github.com/mcardacci)
#### [Ross Wilson](https://github.com/grapefruitricky)
#### [John Lyden](https://github.com/johnlyden)

##Resources
[Heroku Deployment](http://fullbellies.herokuapp.com/)

[Trello Board](https://trello.com/b/KCCdiimC/full-bellies)

[Slack Channel](https://fullbellies.slack.com/messages)

## Installation

```sh
$ git clone [git-repo-url]
$ cd /full-bellies
$ bundle
$ rake db:create
$ rake db:migrate
$ rake db:seed
$ rails s
```
##Technologies
FullBellies uses a number of open source projects to work properly:
* [Bcrypt] - password hashing algorithm, store a secure hash of your users' passwords.
* [Stripe] - allows both private individuals and businesses to accept payments over the Internet
* [Twilio] - programmatically make and receive phone calls and send and receive text messages
* [Sendgrid] - transactional and marketing email through one reliable platform
* [Paperclip] - easy file attachment library for Active Record
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [Google Maps] - a seamless api that provides interactive maps, and satellite/aerial imagery of most countries. 

### Version
1.0.0

### Development

Want to contribute? Great! Feel free to create an issue or open a pull request!

[Twitter Bootstrap]:http://twitter.github.com/bootstrap/
[jQuery]:http://jquery.com
[Paperclip]:https://sendgrid.com/
[Google Maps]:https://developers.google.com/maps/
[Sendgrid]:https://github.com/sendgrid
[Twilio]:https://www.twilio.com/
[Stripe]:https://stripe.com/
[BCrypt]:https://github.com/codahale/bcrypt-ruby

### To Do:

- Integrate sharing with buffer
- Oauth sign-in/up with twitter/FB
- Search deals by geo
- Search deals by vendor
- Opt-in / out of email notificaitons
- Opt-in / ou of sms notifications
- Refactor current code
