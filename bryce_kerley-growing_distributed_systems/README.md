# Growing Distributed Systems

Distributed systems are big, in every sense of the word. From the biggest social
networks and search engines to the simplest web or iOS application, distributed
software causes problems, stemming from its greatest feature: the system 
should continue working even when parts break.

Client applications without network connections still want to capture data, 
backends with a failed service or two shouldn't break the entire application, 
and the app should still mostly work even when the big datacenter (you know the 
one) goes down.

How do you grow a simple monolithic Rails app into a distributed system? What 
does it take to make your UI save data for a network connection later? How do 
you even test all this stuff?

I'll be presenting a survey of concepts, architectures, and experiences, with a 
few tools that make distributed systems less obtuse.

## Bryce Kerley

Bryce organizes the [Miami Ruby Brigade](http://meetup.com/miamirb), 
develops the [Riak Ruby Client](https://github.com/basho/riak-ruby-client) at
Basho, and lives in sunny Miami.

![Profile picture](https://pbs.twimg.com/profile_images/3685687314/f269165e6ff2edf97d8274c1610e099c.jpeg)

- [My website](http://brycekerley.net)
- [My twitter](https://twitter.com/bonzoesc)
- [Past talk slides](https://speakerdeck.com/bryce)
- [Lock it Down with Cryptography, Scottish Ruby Conference 2013](http://programme2013.scottishrubyconference.com/proposals/6/video)
