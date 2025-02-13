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

Knocking this slightly for the structure, but it has great content. If you like a narrative-based that focuses more on the "why", then this is an excellent book. The content is a bit dated in the sense that there resources like [Azure's Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) and [AWS's Well-Architected](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/index.en.html) feel more comprehensive and practical. Regardless, I found ideas like bulkheading directly applicable to multitenant systems I've worked on.
