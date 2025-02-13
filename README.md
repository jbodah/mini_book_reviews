# mini_book_reviews
my brief, opinionated thoughts about various tech, business, and leadership books

#### [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)

⭐⭐⭐⭐

A modern classic book. It's real strength is its breadth of trying to wrap hands around the entirety of distributed systems. It's a really good book that covers a lot of ground, but it is necessarily too brief to be practically useful aside from gathering high-level concepts. The second edition, so far, has a significantly better structure, and I think it will be an easy 5 out of 5.

#### [Database Internals](https://www.databass.dev/)

⭐⭐⭐⭐⭐

A must-read for storage engineers. It is too detailed for generalists but an indispensible resource for anyone who wants to understand the nitty gritty of storage engines and consensus protocols.

#### [Building Microservices, 2nd Edition](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/)

⭐⭐⭐⭐

This is probably the best book out there for generalists. It covers a lot of topics (from code maintenance to reliability to messaging) and has a good mix of breadth and depth (though it definitely leans towards the former). For most people this will be 5 out of 5, but as an infrastructure engineer I found it a bit light on details. I'd still argue it is a must-skim for most developers though.

#### [API Design Patterns](https://www.manning.com/books/api-design-patterns)

⭐⭐

This book has good recommendations, however I find the structure of most Manning books difficult to follow. One issue I have with this book is that the information density is low. I enjoyed chapters like how to represent long-running operations, but I felt that a cheatsheet would have sufficed.

#### [The Design of Web APIs](https://www.manning.com/books/the-design-of-web-apis-second-edition)

⭐⭐

Whereas API Design Patterns is 80% technical, this book is 80% process. It's more about how you go about the process of designing an API than it is about technical constraints. I really like the logical procedure it describes for describing an API (a table of "who, what, inputs, outputs") and have found it an excellent tool during the requirements gathering phase. However, I too find this book to have low information density. It does a good job of setting out what it aims to do (walk you through the steps of gathering requirements and translating those into an API), I just don't personally have a lot of use for this information.

#### [Software Architecture: The Hard Parts](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/)

⭐

I did not enjoy this book and find it extremely long-winded. It is a book that is aimed at architects at very large companies, and I found it less applicable to medium sized ones. The best chapters, by far, are the one on messaging (which attempts to provide a formal process for when you should use async vs. sync messaging) and the one on distributed transactions (orchestration vs. choreography). I like the authors' other books much better, but I found this one far too plodding.

#### [Release It! Second Edition: Design and Deploy Production-Ready Software](https://pragprog.com/titles/mnee2/release-it-second-edition/)

⭐⭐

Knocking this slightly for the structure, but it has great content. If you like a narrative-based that focuses more on the "why", then this is an excellent book. The content is a bit dated in the sense that there resources like [Azure's Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) and [AWS's Well-Architected](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/index.en.html) feel more comprehensive and practical. Regardless, I found ideas like bulkheading directly applicable to multitenant systems I've worked on. The real kicker is the book's emphasis on feedback loops and how they result in failures.

#### [Working with Unix Processes](https://workingwithruby.com/wwup/intro)

⭐⭐⭐⭐⭐

I loved this book. Maybe it's just nostalgia, however this was the book that made multi-processing click for me. It helps that I was experienced in Ruby and working with fork-based worker libraries at the time. I've found the clarity around processes indispensible throughout my career.

#### [Getting to Yes](https://en.wikipedia.org/wiki/Getting_to_Yes)

⭐⭐⭐⭐⭐

Concise, clear, and actionable. I've found the negotiation tactics in this book very useful for working with stakeholders and for driving alignment. Despite it being about "negotiation", it is really about how to resolve conflicts by focusing on understanding what the other side wants, clearly communicating what you want, and trying to emphasize the objective goal of coming to a deal.

#### [Systems Performance: Enterprise and the Cloud, 2nd Edition](https://www.brendangregg.com/blog/2020-07-15/systems-performance-2nd-edition.html)

⭐⭐⭐⭐⭐

The industry standard when it comes to performance engineering. This book is great because it covers both the technical and organizational aspects of performance. I've found its emphasis on [methodologies](https://www.brendangregg.com/methodology.html) particularly enlightening. A fantastic book that I can't recommend enough.

#### [BPF Performance Tools](https://www.brendangregg.com/bpf-performance-tools-book.html)

⭐⭐⭐⭐

Although not as monumental as Systems Performance, I found this specialty book to be immensely useful. This book is more focussed on the development and inner workings of eBPF and bpftrace. It focsues more on specific APIs, event handles, and patterns. Most of the book's useful content can be obtained from cheatsheets, however I still found the long-form explanations useful too.

#### [Understanding Software Dynamics](https://www.oreilly.com/library/view/understanding-software-dynamics/9780137589692/)

⭐⭐⭐

I'm not typically fond of narrative-heavy books, and this books follows that structure. While I found the stories interesting, I found it difficult to extract and retain the big-picture ideas.

#### [The Go Programming Language](https://www.gopl.io/)

⭐⭐⭐⭐

This book is unfortunately a bit dated now and is missing content around several major developments - namely packaging and generics. Still, I found most of the content to be very strong and relevant. The code examples in the book are particularly well chosen for expalining nuances about writing good Go code.

#### [100 Go Mistakes and How to Avoid Them](https://www.manning.com/books/100-go-mistakes-and-how-to-avoid-them)

⭐⭐⭐

After reading other Go books and documentation, I only a found a few of these mistakes novel. Issues like those around looping and variable binding are well-discussed in the Go community these days. If you didn't have a strong foundation or community in Go which could help you get accustomed to the issues, then I think this book would be very valuable. For me, I found the chapters around efficient memory usage and correct synchronization the most useful.

#### [Programming Elixir](https://pragprog.com/titles/elixir16/programming-elixir-1-6/)

⭐⭐⭐⭐⭐

Amazing book that manages to be concise, simple, informative, and technically complex all at the same time. OTP is a challenging model to wrap your head around because it is so much higher level/batteries included compared to your typical programming language. This book covers functional programming, metaprogramming, actors, and OTP applications hitting on the most important aspects of each.

#### [Exercises for Programmers: 57 Challenges to Develop Your Coding Skills](https://pragprog.com/titles/bhwb/exercises-for-programmers/)

⭐

I wanted to like this book, however I found the coding challenges to be wholly impractical focusing more on the puzzle side of programming rather than getting-things-done side. I was really hoping for a set of tasks that you could use to efficiently learn the standard library of many programming languages (read a file, make an HTTP request), but I didn't find it very useful in that regard.

#### [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/)

⭐⭐⭐⭐

A very useful and extremely relevant book on how, organizationally, to run a large production application well. The content starts off high quality and then tapers off around the midpoint as topics become less tangible and less evidence-based. Chapters around effective monitoring, incident management, and SLOs are must-reads. A foundational book even if half of it isn't useful.
