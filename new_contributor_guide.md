## Guide for New Contributors

Hello, and welcome to the Rust-ML group! We're glad you may be interested in 
contributing to our efforts. First, please take the time to review our main [README](./README.md)
document, particularly around the "What do we do" section. 

In general, the Rust-ML group emphasizes the [Bazaar, not the Cathedral](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar). In the 
[Zulip chat](https://rust-ml.zulipchat.com/), we regularly see people who say "Hi, I'm new here and would love to 
help contribute!" under the assumption that there may be a comprehensive Grand \
Plan that they can be directed towards. While well-intentioned, this approach is 
a little difficult to respond to because, although some individual projects do 
have roadmaps, the working group is not a Group with a Plan, but instead a collection 
of individuals working on things they're personally interested in. 

We recommend you start by looking through the chat history in Zulip (particularly 
in the [#Code Review](https://rust-ml.zulipchat.com/#narrow/stream/237158-Code-Review) stream, which will have discussion of some of the more active 
projects) to see if there's something pre-existing that you might be interested in 
contributing to. Members of the Rust-ML team also help to maintain the site 
[arewelearningyet.com](https://www.arewelearningyet.com/), which has a more comprehensive list of crates and other 
projects in the Rust ecosystem. Alternatively, if you *don't* find something like that, 
write your own and share it with us! 

### Low Hanging Fruit

One of the few projects that the Rust-ML group has direct ownership of and maintains
is the [linfa](https://github.com/rust-ml/linfa/) classical machine learning meta-crate. It serves as a collection of multiple 
smaller algorithms in various domains. Although the implementations of the algorithms
themselves usually exist and have some degree of testing, the crate as a whole can 
use some additional work in the areas of cross-language testing and benchmarking. 
[Luca Palmieri](https://github.com/LukeMathWalker), the original author of the linfa crate, did some great work on demonstrating 
the potential speed-ups of using Rust code for a k-means clustering algorithm by writing 
Rust->Python bindings and [comparing](https://www.lpalmieri.com/posts/2019-12-01-taking-ml-to-production-with-rust-a-25x-speedup/) the results against scikit-learn's implementation. 

Creating a similar repository for each of linfa's sub-crates, or creating regression 
benchmarks for the sub-crates would be a great first contribution. Similarly, the 
documentation in terms of overall workflow for using Rust in a machine learning 
problem from scratch is somewhat limited. A Book [repository](https://github.com/rust-ml/book) has been created
to help create a guide for newcomers, but is currently missing some content. 
Building a project using any of the crates in the ecosystem to solve a problem and
 clearly documenting that process would also be helpful to the community!

### A closing reminder

Although some of the people who write code will lay out some sort of a larger 
roadmap or fill a leadership role to a degree, project management is rarely a 
full-time concern, especially for projects with a relatively low number of contributors. 
Therefore, it's usually best to approach things from a "code first, communicate after." 
As in all open source projects you will get a faster response for a well-written bug 
report or pull request. Also sometimes people are busy with their life and can't 
spend time on their side projects. Please respect that we're all human and have 
limited time.

### Updated 

Updated on 20201024
