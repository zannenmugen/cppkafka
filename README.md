This library provides a high level C++ interface for rdkafka. It allows applications to send and receive messages using the Apache Kafka protocol. The tool uses modern C++ features to make coding easier while maintaining low overhead. 

The software supports both producing and consuming messages. Consumption works through a high level API. You must have rdkafka version 0.9.4 or higher to use it. Versions starting from 0.11.4 support message headers. The library adds very little processing time over the base tool. 

The interface is designed for simplicity. You can create a configuration with a broker list and start a producer with only a few lines of code. The producer can send a message to a specific topic and partition then clear the buffer. 

To compile the code you need a compiler with C++11 support and the boost library. You also need CMake and the base rdkafka files. The build process involves creating a build folder then running the standard cmake and make commands. 

There are several options you can set during the build process. You can change the install path for dependencies or choose to build a shared library. You can also turn off tests or examples to speed up the process. 

When you use this in your own project you must link against both the wrapper and the base library. If you use CMake you can find the package and link the target libraries directly. 

You can create local documentation in html format if you have Doxygen installed. The project wiki contains more details about specific features and usage guides.
