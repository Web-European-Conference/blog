
* *Tell us a bit more about your session*

My session is about "Reactive Extensions" (Rx); speaking about Rx is really exciting because in our work it's rare to find something really new, but Rx, with its Observable pattern, somehow did it.

It showed us something that even the venerable [Gang of Four](http://c2.com/cgi/wiki?GangOfFour) in their "Design Pattern" book missed, that [Iterator](https://en.wikipedia.org/wiki/Iterator_pattern) and [Observer](https://en.wikipedia.org/wiki/Observer_pattern) patterns were really different views of the same thing, quite interesting stuff.

In the first half of the session we will introduce the Observable pattern as it was introduced historically, as a way to make [Iterator pattern](https://en.wikipedia.org/wiki/Iterator_pattern) *Async* and then we will show the similarities with the [Observer pattern](https://en.wikipedia.org/wiki/Observer_pattern) and how, at the end of the day, Rx team at Microsoft, *noticed* also that this new pattern was also able to express [Promises](https://en.wikipedia.org/wiki/Futures_and_promises) (the cornerstone of modern async programming).

At that point, with a lot of theory but zero code written, we will start a small demo about how to use Observable in Javascript using the [RxJS library](https://github.com/Reactive-Extensions/RxJS).

Then we will start to introduce other aspects of Rx (mainly grammar and operations to manipulate Observables) and we will end up with a more complex demo of an [autocomplete](https://en.wikipedia.org/wiki/Autocomplete) webpage written using Rx.

Then we have to briefly introduce Rx schedulers (briefly because schedulers are of huge importance in Rx implementations for other languages but, since Javascript is single-threaded, RxJS schedulers are few and usually the default RxJS choice is approriate for common use cases and rarely one needs to handle them directly).

If i've still space I would like to share the same tutorial reference i'll add at the end of the presentation for people who wants to deepen the topic.

 * **[ReactiveX](http://reactivex.io/)**: Homepage of RX project.
 * **[LearnRX](http://reactivex.io/learnrx/)**: Online tutorial, published initially by Netflix as training for its developers.
 * **[RxJSKoans](https://github.com/Reactive-Extensions/RxJSKoans)**: GitHub repository full of small exercises of increasing difficulty using RxJS.
 * **[Rx Workshop](https://channel9.msdn.com/Series/Rx-Workshop)**: A set of videos teaching you Rx.NET directly from Rx team members.

* *Tell us a bit more about yourself*

First of all i'm a software developer, even if after 10 years of experience, as you can imagine, my role in the company changed quite a lot.

I'm a [Cluster Reply](http://www.reply.eu/en/) employee and my current title is something like *"Solution Architect"* and *"Technical Advisor"*, and what it really means to me is just being a software developer with added responsability such as teaching and introducing colleagues to new technologies, patterns and architectures and, obviously, be blamed when something don't work out as intended.

My main interest is about *message-oriented middleware* and *integration systems* because I discovered soon, thanks to the ubiquity of internet and IP protocol, that **every** system (yes, websites too) we realize these days has strict integration/communication requirements and satistying them (with SOA, ESB, EAI, Microservices or whatever) is probably one of the most important part of every IT project.

To quote Michael Nygard "Release It!" wonderful book:

> I haven't seen a "pure-website" project since about 1996.
> If your projects are like mine, they have probably been
> enterprise integration projects that happen to have an HTML-based front end.
