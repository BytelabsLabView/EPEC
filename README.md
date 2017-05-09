# EPEC
EventProducerEventConsumer DesignPattern

This is just our idea to built a unique method to communicate, from starting to a QMH design pattern.

In QMH we use UserEventMessages to communicate with event, could be use User Event to manage all messages? Can we have N:N and N:1 messages with event?

An inspiration for this work is the use of simple sub-stations instead of xcontrol that create some unmanageable problems especially in distribution. This inspiration starts with reading this article http://www.notatamelion.com/tag/xcontrols/.

We don't discuss about xcontrol issues, but we focus around use event instead the queue, and about use one only method to communicate and whats is the case in which we can use it.

