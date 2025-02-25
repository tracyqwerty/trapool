# Multithreading Knowledge Sharing

Here I'd like to cover most basic concepts and usages of multithreading! Powered by ChatGPT4. 

Let's start our journey >w<.

## Trapool

A thread pool implemented in cpp. 

* [A Brief Introduction to Threadpool](trapool/docs/threadpool.md)

* [The producer-consumer (bounded-buffer) problem](trapool/docs/producer&consumer.md)

## Concepts

[`process & thread`](docs/process&thread.md)

## Examples

Example codes of basic elements's usage.

* [`hello world!`](examples/1.hello_world.cpp)
* [`join`](examples/2.join.cpp)
* [`detach`](examples/3.detach.cpp)
* [`deadlock`](examples/4.deadlock.cpp)
* [`semaphore`](examples/5.semaphore.cpp)
* [`condition variable`](examples/6.condition_variable.cpp)
* [`std::future & std::primise`](examples/7.future&promise.cpp)
* [`std::async`](examples/8.async.cpp)
* [`multithread`](examples/9.multithread.cpp)
* [`two-phase locking (2PL)`](examples/10.two_phase_locking.cpp)

## Leetcode

Multithread-related leetcode problems.

| Question                                                     | Status   |
| ------------------------------------------------------------ | -------- |
| [1114.Print in Order](https://leetcode.com/problems/print-in-order/) | `Solved` |
| [1115.Print FooBar Alternately](https://leetcode.com/problems/print-foobar-alternately/) | `Solved` |
| [1116.Print Zero Even Odd](https://leetcode.com/problems/print-zero-even-odd/) | `Solved` |
| [1117.Building H2O](https://leetcode.com/problems/building-h2o) |          |
| [1188.Design Bounded Blocking Queue](https://leetcode.com/problems/design-bounded-blocking-queue) | `Locked` |
| [1195.Fizz Buzz Multithreaded](https://leetcode.com/problems/fizz-buzz-multithreaded) |          |
| [1226.The Dining Philosophers](https://leetcode.com/problems/the-dining-philosophers) |          |
| [1242.Web Crawler Multithreaded](https://leetcode.com/problems/web-crawler-multithreaded) | `Locked` |
| [1279.Traffic Light Controlled Intersection](https://leetcode.com/problems/traffic-light-controlled-intersection) | `Locked` |



## Reference

https://paul.pub/cpp-concurrency/

https://paul.pub/cpp-memory-model/

https://github.com/progschj/ThreadPool

https://github.com/anthonywilliams/ccia_code_samples
