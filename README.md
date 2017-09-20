# Core - Google and Stack Overflow


## Google 

How do you use Google? Do you rely on the top search results? 

https://www.wired.com/2011/11/st_thompson_searchresults

You should be assessing the results and deciding whether the 
answers are reliable and on topic. 

When you search these are questions you should be asking: 

- How accurately do these results match the answer I'm looking for?
- How credible/knowledgeable is the source?
  - When was this answer published?

### Google more effectively

Use effective keywords. The more descriptive you can be 
the better your results.

Google matches key words it doesn't answer questions.
Identify key words. 

- A who
- The Who
- Who

Order matters 
- Sky Blue 
- Blue Sky

Search term modifiers:

- http://mashable.com/2011/11/24/google-search-infographic/#yMlfd4pRaGqW

### On searching error messages

When confronted with an error message you'll need to identify the 
section that best describes the error. Usually the best 
information will at the top of an error. 

Many times part of the error will contain identifiers that you 
have created these may not be relevant. 

```
Playground execution failed: error: Equatable.playground:5:25: error: 'Self' is only 
available in a protocol or as the result of a method in a class; did you mean 'Person'?
    static func ==(lhs: Self, rhs: Self) -> Bool {
                        ^~~~
                        Person

error: Equatable.playground:5:36: error: 'Self' is only available in a protocol or 
as the result of a method in a class; did you mean 'Person'?
    static func ==(lhs: Self, rhs: Self) -> Bool {
                                   ^~~~
                                   Person

* thread #1, queue = 'com.apple.main-thread', stop reason = breakpoint 1.1
  * frame #0: 0x000000010c83d360 com.apple.dt.Xcode.PlaygroundStub-macosx`executePlayground
    frame #1: 0x000000010c83b22a com.apple.dt.Xcode.PlaygroundStub-macosx`-[PlaygroundViewBridgeService execute] + 90
    frame #2: 0x00007fff80187b8c CoreFoundation`__invoking___ + 140
    frame #3: 0x00007fff80187a11 CoreFoundation`-[NSInvocation invoke] + 289
    frame #4: 0x00007fff801a1196 CoreFoundation`-[NSInvocation invokeWithTarget:] + 54
    frame #5: 0x00007fff93a923d6 ViewBridge`__68-[NSVB_ViewServiceImplicitAnimationDecodingProxy forwardInvocation:]_block_invoke + 47
    frame #6: 0x00007fff93ab0fe9 ViewBridge`__runAnimationGroup_block_invoke + 21
    frame #7: 0x00007fff7e5d1846 AppKit`+[NSAnimationContext runAnimationGroup:] + 58
    frame #8: 0x00007fff7dc99bea AppKit`+[NSAnimationContext runAnimationGroup:completionHandler:] + 85
    frame #9: 0x00007fff93ab0fc5 ViewBridge`runAnimationGroup + 303
    frame #10: 0x00007fff93a91edd ViewBridge`+[NSVB_View _animateWithAttributes:animations:completion:] + 507
    frame #11: 0x00007fff93a92358 ViewBridge`-[NSVB_ViewServiceImplicitAnimationDecodingProxy forwardInvocation:] + 156
    frame #12: 0x00007fff8018654a CoreFoundation`___forwarding___ + 538
    frame #13: 0x00007fff801862a8 CoreFoundation`__forwarding_prep_0___ + 120
    frame #14: 0x00007fff80187b8c CoreFoundation`__invoking___ + 140
    frame #15: 0x00007fff80187a11 CoreFoundation`-[NSInvocation invoke] + 289
    frame #16: 0x00007fff801a1196 CoreFoundation`-[NSInvocation invokeWithTarget:] + 54
    frame #17: 0x00007fff93a608a2 ViewBridge`-[NSVB_QueueingProxy forwardInvocation:] + 327
    frame #18: 0x00007fff8018654a CoreFoundation`___forwarding___ + 538
    frame #19: 0x00007fff801862a8 CoreFoundation`__forwarding_prep_0___ + 120
    frame #20: 0x00007fff80187b8c CoreFoundation`__invoking___ + 140
    frame #21: 0x00007fff80187a11 CoreFoundation`-[NSInvocation invoke] + 289
    frame #22: 0x00007fff801a1196 CoreFoundation`-[NSInvocation invokeWithTarget:] + 54
    frame #23: 0x00007fff8018654a CoreFoundation`___forwarding___ + 538
    frame #24: 0x00007fff801862a8 CoreFoundation`__forwarding_prep_0___ + 120
    frame #25: 0x00007fff80187b8c CoreFoundation`__invoking___ + 140
    frame #26: 0x00007fff80187a11 CoreFoundation`-[NSInvocation invoke] + 289
    frame #27: 0x00007fff801a1196 CoreFoundation`-[NSInvocation invokeWithTarget:] + 54
    frame #28: 0x00007fff8018654a CoreFoundation`___forwarding___ + 538
    frame #29: 0x00007fff801862a8 CoreFoundation`__forwarding_prep_0___ + 120
    frame #30: 0x00007fff80187b8c CoreFoundation`__invoking___ + 140
    frame #31: 0x00007fff80187a11 CoreFoundation`-[NSInvocation invoke] + 289
    frame #32: 0x00007fff93ab5579 ViewBridge`withHintInProgress + 487
    frame #33: 0x00007fff93ab52b0 ViewBridge`__deferNSXPCInvocationOntoMainThread_block_invoke_2 + 233
    frame #34: 0x00007fff93a39459 ViewBridge`+[NSViewServiceApplication withHostPID:invoke:] + 46
    frame #35: 0x00007fff93ab5173 ViewBridge`__deferNSXPCInvocationOntoMainThread_block_invoke + 179
    frame #36: 0x00007fff93ab4d67 ViewBridge`__deferBlockOntoMainThread_block_invoke_2 + 544
    frame #37: 0x00007fff801aa17c CoreFoundation`__CFRUNLOOP_IS_CALLING_OUT_TO_A_BLOCK__ + 12
    frame #38: 0x00007fff8018af84 CoreFoundation`__CFRunLoopDoBlocks + 356
    frame #39: 0x00007fff8018aac6 CoreFoundation`__CFRunLoopRun + 1878
    frame #40: 0x00007fff8018a114 CoreFoundation`CFRunLoopRunSpecific + 420
    frame #41: 0x00007fff7f6eaebc HIToolbox`RunCurrentEventLoopInMode + 240
    frame #42: 0x00007fff7f6eacf1 HIToolbox`ReceiveNextEventCommon + 432
    frame #43: 0x00007fff7f6eab26 HIToolbox`_BlockUntilNextEventMatchingListInModeWithFilter + 71
    frame #44: 0x00007fff7dc83a54 AppKit`_DPSNextEvent + 1120
    frame #45: 0x00007fff7e3ff7ee AppKit`-[NSApplication(NSEvent) _nextEventMatchingEventMask:untilDate:inMode:dequeue:] + 2796
    frame #46: 0x00007fff93a3a628 ViewBridge`-[NSViewServiceApplication nextEventMatchingMask:untilDate:inMode:dequeue:] + 100
    frame #47: 0x00007fff7dc783db AppKit`-[NSApplication run] + 926
    frame #48: 0x00007fff7dc42e0e AppKit`NSApplicationMain + 1237
    frame #49: 0x00007fff95b638c7 libxpc.dylib`_xpc_objc_main + 775
    frame #50: 0x00007fff95b622e4 libxpc.dylib`xpc_main + 494
    frame #51: 0x00007fff93a64c85 ViewBridge`-[NSXPCSharedListener resume] + 16
    frame #52: 0x00007fff93a3f316 ViewBridge`NSViewServiceApplicationMain + 2985
    frame #53: 0x000000010c83d3a2 com.apple.dt.Xcode.PlaygroundStub-macosx`main + 34
    frame #54: 0x00007fff9590a235 libdyld.dylib`start + 1
```

Try these searches. Imagine you want to: 

1. Learn how to rearrange the elements of an collection?
2. Understand how random are random numbers?
3. Get maximum randomness out of random numbers?
4. Find a service that delivers very random numbers?

### Resources

- http://www.lifehack.org/articles/technology/20-tips-use-google-search-efficiently.html
- http://www.byrdseed.com/teaching-search-skills/

### Google Utilities

1. Definition
2. Calculator
3. Timer
4. Conversions
5. Games
6. Easter eggs
7. Do a barrel roll
8. Zerg Rush

## Stack Overflow

> Stack Overflow is a question and answer site for professional and enthusiast 
> programmers. It's built and run by you as part of the Stack Exchange network of 
> Q&A sites. With your help, we're working together to build a library of detailed 
> answers to every question about programming.

**Stack Overflow is a great place to find answers.**

There are Stack Exchanges for almost every topic.

- https://stackexchange.com/sites

### Tour Stack Overflow

- https://stackoverflow.com/tour

It also a good place to build a reputation. This is good for 
job applications. 

People can be snarky. Ignore rude behavior if you encounter it. 
do not take any conversation on the internet personally. 
Remember! While diamonds last a life time the internet is forever!

What to look for when reading a question. 

What to look for in an answer. Read the comments. 

When asking questions: 
  - Write a clear description. Short and to the point. 
  avoid unnecessary language. Terse but accurate. 
  - Include a code snippet. Use Stack Overflow's formmatting. 
  
When answering questions: 
  - Write a clear and intelligable answer. 
  - Avoid extraneous language. 
  - Use formmatting 
  - Answer your own questions when you can. 
  
Developper stories. 

### Activities

1. Make an account on Stack Overflow. 
2. Search for a solution to the random array? 
  - Add a comment. 
  - Up vote the answer you agree is best. 
3. Ask a question. 
  - Think of a question you had this week. 
  - Post the question. 
    - Notice the question may already exist! The site suggests existing questions. 
    - Explain your question as clearly and concisely as you can. 
      - Format your answer!
    - Use tags. Follow the rules for tags. 
4. Look at new questions and try your best to provide an answer. 
  - Format your answer. 
  - Write a good answer. Keep it clear and concise. 
  
- Who can get the highest rep? 
- Did anyone earn a badge?

### Developer Stories

This is a feature that acts like your resume on Stack Overflow. You can build it 
over time. 

- https://stackoverflow.com/users/story/join

Start your developer story. 

### Developer Survey

Stack Overflow provides a great look into the world of developers. What they 
do in what quantities, who they are (sort of), and where and what they work on. 

- https://insights.stackoverflow.com/survey/2017

What are some outstanding facts? 

