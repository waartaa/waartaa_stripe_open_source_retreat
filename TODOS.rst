TODOS
=====

- HTML5 mobile interface for Waartaa

  Implement a mobile optimized client for Waartaa. This will basically be
  a web app which can run on mobile browser, Firefox OS, as a native app (
  using Phonegap) as well. Some major differences of the mobile web app from
  the desktop web app will be:

  - **Less subscriptions to data**. Subscribe for data elements which need to
    be rendered in the UI.
  - **On demand loading of data**. This will take some time, but it will be
    memory savvy.

- Build APIs, bots for seamless 3rd party integration

  Integration with 3rd party services like Bugzilla, git (and other VCS), trac,
  etc. have always existed in the IRC world, using bots. However, there are
  some common steps involved:

  - Write code for the bot, if someone hasn't already done it
  - Run the bot in a server
  - Monitor and maintain it

  We want to make this process simpler by allowing one click setup of a channel
  bot with optional integration to 3rd party services supported by Waartaa. We
  also need to come up with a friendly API to empower the community to
  integrate a new service with Waartaa.

- Enable scaling Waartaa

  Currently, Waartaa is made to run on a single server only. We need to
  separate the layers: application, IRC, etc. and run them as different
  processes in the same or different machines. This will help us to have
  NxM combination of application and IRC servers, and will help us balance
  the load on Waartaa. Also, optimization will be needed at the database layer
  to handle increased writes and reads.

- Improve on audio/video communication integration done during GSoC

  It's in our tasklist to do a basic integration of audio/video communication
  using WebRTC during GSoC 2014. However, we need to revisit this feature
  and improve it to make it usable by loads of users of Waartaa.

- Easy setup and deployment

  Write scripts, and package Waartaa for easy setup and deployment of Waartaa.

- Distributed log storage

  Allow users to share space from their cloud storage (Dropbox, Google drive,
  etc.) where Waartaa can dump their logs into small files. The data from these
  files can be viewed from Waartaa from the log browser. This distributed 
  storage model will allow Waartaa service providers to operate with less
  server storage without compromising on the realtime nature of Waartaa. It
  will not be easy for users to search through all logs at once, but Waartaa
  will put its best efforts to perform as much as possible in limited resources
  too.

- Encrypt private user logs

  Give the user option to for encrypted storage of private chat logs in the
  server. This will come with some trade off for servr side search in the
  encrypted logs. But, this is a price one may be willing to pay for privacy.
  Waartaa aims at providing options to the user to take ownership of their
  data.

- Secure authentication with IRC servers

  IRC servers do authentication with raw text passwords. That's why, we do not
  store NickServ passwords in Waartaa at this moment. However, it's not at all
  user friendly to authenticate manually to IRC servers everytime a user joins
  a server. Waartaa needs to figure out a way to store user passwords in a safe
  way so that admins of the Waartaa service don't have a way to pick into
  user's IRC passwords from the database or the system.

- Wizard to help new users find channels they are looking for
- API to export logs
- Friend finder
- Improve UX

  - keyboard shortcuts for navigation
  - customizable color schemes
  - In page integration with paste services like gist, pastebin, etc.
  - UI endpoint for most IRC (server) commands
  - Autocomplete IRC (server) commands, along with commands cheatlist
