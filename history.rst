The need for a better communication tool for IRC is nothing new. It had been
existing for a long time (since our days in college, when we started with
FOSS). Some of the problems we faced were (are):

- low internet bandwidth
- frequent disconnection of internet connection
- sometimes no connection at all
- IRC ports blocked on college network
- No persistent logs with existing web IRC clients

Apart from that, it took some learning to get started with communication on
IRC and the IRC clients:

- IRC servers (IPs, ports, SSL)
- channels
- PM
- IRC ports

A communication tool that requires some learning is a failure in itself. Not
every one is a geek. If some one is handed a IRC client, there's no straight
forward way to make good use of it. We're a bit lucky in this case that we
got introduced to FOSS first and then too IRC, and there were people who
showed us how to use these tools. But there are many who have little knowledge
about FOSS, IRC, etc. and no one to guide them as well.

After college, when I started working, I used to work from multiple machines.
Although, I used to use a bot in a remote ZNC server, syncing logs across
machines became a pain. Then I got myself a Macbook, and purchased Linkinus
(a IRC client). It's so intuitive and sleek. After using Linkinus, I started
hating the other not so beautiful IRC clients. And then, at work, we moved from
IRC to HipChat. Life became so easy after migrating to Hipchat, may be for
the following reasons:

- Beautiful web and native clients
- Accessible from anywhere and multiple devices
- Centralized logging
- 24x7 idling
- Mail notifications when away
- search interface for chat logs
- Realtime

But, one has to be on IRC for communication with FOSS communities. I badly
wanted to build my own IRC client on the cloud, a realtime one, inspired by
HipChat, but I was too lazy to do it due to the complexity involved in
building a realtime application. Then, one day, I came across
`Meteor <www.meteor.com>`_, which made developing realtime apps a breeze. This
was the framework I have been subconsciously waiting for. With Meteor taking
care of the realtime communication part, it was very easy for me to focus and
start working on Waartaa.

Sayan was able to relate himself with the mission of Waartaa. Why wouldn't he?
After all, he had similar experience as mine with IRC communication. He started
contributing to Waartaa and taking active participation in brainstorming
features, UX and evangelising Waartaa alongside me.

After months of efforts, usually before or after office hours and weekends, we
came up with an initial prototype of Waartaa with very limited but important
featureset:

- Centralized logging
- 24x7 idling
- Mail notifications
- Unique identity (across multiple devices)

Currently, I and Sayan have been maintaining Waartaa and building new features.
Waartaa has attracted quite some attention in the community. We're able to push
Waartaa as a project idea for GSoC 2014 under the umbrella of the
Fedoraproject. We received a good number of applications from students across
the globe, among which we selected one applicant, Lalit, to hack on Waartaa
this summer for GSoC for the Fedoraproject. We are mentoring Lalit to grow
as a contributor in Waartaa and play an important role with us in shaping
the development of open communication and collaboration tools.
