<div id="logo" align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/go/go-original-wordmark.svg" width="200px"/>
</div>

# golang
Useful links about go

## Runtime

### Common
1. [Visualizing Garbage Collection Algorithms](https://spin.atomicobject.com/2014/09/03/visualizing-garbage-collection-algorithms/) - Ken Fox
2. [Tracing Garbage Collection](https://en.wikipedia.org/wiki/Tracing_garbage_collection) - Wikipedia
3. [On-the-Fly Garbage Collection: An Exercise in Cooperation](https://lamport.azurewebsites.net/pubs/garbage.pdf) - Edsger W. Dijkstra
---

### The Golang Scheduler
1. [The Golang Scheduler](https://www.kelche.co/blog/go/golang-scheduling/) - Kevin Kelche
1. [Scheduling In Go : Part I - OS Scheduler](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html) - William Kennedy
1. [Scheduling In Go : Part II - Go Scheduler](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part2.html) - William Kennedy 
1. [Scheduling In Go : Part III - Concurrency](https://www.ardanlabs.com/blog/2018/12/scheduling-in-go-part3.html) - William Kennedy
1. [Планирование в Go: Часть I — Планировщик ОС](https://habr.com/ru/articles/478168/) - William Kennedy (перевод)
1. [Планирование в Go: Часть II — Планировщик Go](https://habr.com/ru/articles/489862/) - William Kennedy (перевод)
1. [Планирование в Go: Часть III — Конкурентность](https://habr.com/ru/articles/761606/) - William Kennedy (перевод)
1. [Understanding the Go Scheduler and discovering how it works](https://medium.com/@sanilkhurana7/understanding-the-go-scheduler-and-looking-at-how-it-works-e431a6daacf) - Sanil Khurana
1. :movie_camera: [Go scheduler: Implementing language with lightweight concurrency](https://www.youtube.com/watch?v=-K11rY57K7k) - Dmitry Vyukov
1. :movie_camera: [Планировщик Go](https://www.youtube.com/watch?v=TRoFIaHdjB8) - ТиПМС 9
---

### Go GC
1. [A Guide to the Go Garbage Collector](https://go.dev/doc/gc-guide)
2. [runtime/mgc.go](https://github.com/golang/go/blob/dev.boringcrypto.go1.17/src/runtime/mgc.go#L5)
3. [Go 1.5 concurrent garbage collector pacing](https://docs.google.com/document/d/1wmjrocXIWTr1JxU-3EQBI6BK6KgtiFArkG47XK73xIQ/edit#heading=h.xy314pvxblbm) - Google
4. [GC scanning of stacks](https://docs.google.com/document/d/1un-Jn47yByHL7I0aVIP_uVCMxjdM5mpelJhiKlIqxkE/edit#heading=h.bvezjdnoi4no) - Google
5. [Go Blog - Go GC: Prioritizing low latency and simplicity](https://go.dev/blog/go15gc) - Richard Hudson
6. [Go Blog - Getting to Go: The Journey of Go's Garbage Collector](https://go.dev/blog/ismmkeynote) - Richard Hudson
7. :movie_camera: [Go GC: Solving the Latency Problem](https://www.youtube.com/watch?v=aiv1JOfMjm0&list=PL2ntRZ1ySWBf-_z-gHCOR2N156Nw930Hm&index=17) - Rick Hudson
8. [Golang’s Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/) - Will Sewell
9. [Concurrent garbage collection](https://github.com/rubinius/rubinius-website-archive/blob/cf54187d421275eec7d2db0abd5d4c059755b577/_posts/2013-06-22-concurrent-garbage-collection.markdown) - Dirkjan Bussink
10. [Why golang garbage-collector not implement Generational and Compact GC?](https://groups.google.com/g/golang-nuts/c/KJiyv2mV2pU)
11. [How Does the Garbage Collector Mark the Memory?](https://medium.com/a-journey-with-go/go-how-does-the-garbage-collector-mark-the-memory-72cfc12c6976) - Vincent Blanchon
12. [How Does the Garbage Collector Watch Your Application?](https://medium.com/a-journey-with-go/go-how-does-the-garbage-collector-watch-your-application-dbef99be2c35) - Vincent Blanchon
13. [How Does the Garbage Collector Mark the Memory?](https://medium.com/a-journey-with-go/go-how-does-the-garbage-collector-mark-the-memory-72cfc12c6976) - Vincent Blanchon
14. [Memory Management and Allocation](https://medium.com/a-journey-with-go/go-memory-management-and-allocation-a7396d430f44) - Vincent Blanchon
15. [Go scheduling and Garbage collection](https://medium.com/@openmohan/go-scheduling-and-garbage-collection-91b5144bc26b) - Mohan Prasath
16. [Garbage Collection In Go : Part I - Semantics](https://www.ardanlabs.com/blog/2018/12/garbage-collection-in-go-part1-semantics.html) - William Kennedy
17. [Garbage Collection In Go : Part II - GC Traces](https://www.ardanlabs.com/blog/2019/05/garbage-collection-in-go-part2-gctraces.html) - William Kennedy
18. [Garbage Collection In Go : Part III - GC Pacing](https://www.ardanlabs.com/blog/2019/07/garbage-collection-in-go-part3-gcpacing.html) - William Kennedy
19. [Go’s march to low-latency GC](https://blog.twitch.tv/en/2016/07/05/gos-march-to-low-latency-gc-a6fa96f06eb7/#2f2f) - Rhys Hiltner
20. [Почему Discord переходит с Go на Rust](https://habr.com/ru/post/487116/)
21. [Предотвращаем утечки памяти в Go, ч. 1. Ошибки бизнес-логики](https://habr.com/ru/company/ncloudtech/blog/675390/) - Виталий Исаев
22. [Предотвращаем утечки памяти в Go, ч. 2. Ошибки бизнес-логики](https://habr.com/ru/company/ncloudtech/blog/676960/) - Виталий Исаев
23. [Анализ механизма сбора мусора Go](https://russianblogs.com/article/3396205378/)
24. [In-depth analysis of Golang's GC scanning object implementation](https://blog.600mb.com/a?ID=01750-8ccdc0e3-5fd3-47c1-a302-88bf6c5be2fa)
25. :movie_camera: [Как устроен garbage collector в Go 1.9](https://www.youtube.com/watch?v=CX4GSErFenI) - Андрей Дроздов, Avito
26. :movie_camera: [Как устроена сборка мусора в Golang](https://www.youtube.com/watch?v=CX4GSErFenI) - Дмитрий Кривенко
27. :movie_camera: [P99 Conf Logo 2022: Large-Scale, Semi-Automated Go Garbage Collection Tuning at Uber](https://www.youtube.com/watch?v=vmFWSGE51w0) - Cristian Velazquez, Uber
28. :movie_camera: [GopherCon 2019: The garbage collector](https://www.youtube.com/watch?v=gPxFOMuhnUU) - Maya Rosecrance
29. :movie_camera: [GopherCon 2022: Control Theory and Concurrent Garbage Collection Deep Dive](https://www.youtube.com/watch?v=We-8RSk4eZA&list=PL2ntRZ1ySWBfiSJSt-zPRbVSMDfK0EwQC) - Madhav Jivrajani
30. :movie_camera: [GopherCon Singapore 2019: Garbage Collection Semantics](https://www.youtube.com/watch?v=q4HoWwdZUHs) - William Kennedy
31. :movie_camera: [Ozon Go Meetup Moscow 2022](https://www.youtube.com/watch?v=PB4vA5eId4c) - Moguchev Leonid
---

### Memmory 
1. [Structure size optimization in Golang (alignment/padding). More effective memory layout (linters)](https://itnext.io/structure-size-optimization-in-golang-alignment-padding-more-effective-memory-layout-linters-fffdcba27c61) - Roman Romadin
2. [Breaking the Type System in Golang (aka dynamic types)](https://medium.com/@utter_babbage/breaking-the-type-system-in-golang-aka-dynamic-types-8b86c35d897b) - Sidhartha Mani
3. [Механизмы выделения памяти в Go](https://www.youtube.com/watch?v=CX4GSErFenI) - Дмитрий Кривенко
4. :movie_camera: [Потребление оперативной памяти в языке Go: проблемы и пути решения](https://www.youtube.com/watch?v=_BbhmaZupqs) - Виталий Исаев, МойОфис
5. :movie_camera: [GopherCon UK 2018: Understanding Go's Memory Allocator](https://www.youtube.com/results?search_query=go+garbage+collector) - Andre Carvalho
6. :movie_camera: [Memory Management in Go: The good, the bad and the ugly. GopherCon UK 2023](https://youtu.be/SKenR18NM04?si=G5Ae7OSH9WuO8PDu) - Liam Hampton
---

### sync.Pool
1. [Go: понять дизайн Sync.Pool](https://dev-gang.ru/article/go-ponjat-dizain-syncpool-cpvecztx8e/)
2. [Using sync.Pool](https://developer20.com/using-sync-pool/)
---

### Channels
1. :movie_camera: [Go Channels Internals](https://www.youtube.com/watch?v=Tp5xhTMFuLU) - Егор Гришечко
1. :movie_camera: [Как на самом деле устроены каналы в Golang](https://www.youtube.com/watch?v=ZTJcaP4G4JM) - Николай Тузов
1. :movie_camera: [Внутреннее устройство каналов в Go](https://www.youtube.com/watch?v=ZTJcaP4G4JM) - Николай Тузов
---

### Maps
1. :movie_camera: [Как на самом деле устроен тип Map в Golang?]([https://www.youtube.com/watch?v=P_SXTUiA-9Y](https://www.youtube.com/watch?v=P_SXTUiA-9Y)) - Николай Тузов
1. :movie_camera: [Go Map Internals](https://www.youtube.com/watch?v=3n1QkOI-y2g) - Егор Гришечко
