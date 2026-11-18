![Robotweax — Intelligence. In every stream. Video, Broadcast, Networking.](assets/robotweax-header.png)

We develop software for video streaming, broadcast, networking and intelligent automation. This is the home of our public engineering projects.

### Robotweax SRT

An independent, open-source implementation of **Secure Reliable Transport** in C++20, with the public SRT C API. For developers building media applications, integrating SRT, or evaluating transport behavior.

Pre-1.0. Compatibility and qualification limits are documented per release.

[Source](https://github.com/Robotweax/srt) · [Releases](https://github.com/Robotweax/srt/releases) · [Examples](https://github.com/Robotweax/srt/tree/main/examples) · [Compatibility](https://github.com/Robotweax/srt/blob/main/docs/compatibility.md)

### GNU Radio over SRT

**gr-robotweax-srt** connects GNU Radio flowgraphs over IP networks. Its SRT Source and Sink blocks carry real and complex sample streams, with bounded buffering, capture-time tags and explicit reporting of gaps and discontinuities.

Release candidate. Tests use synthetic signals; acquisition hardware and field readiness remain unqualified.

[Source](https://github.com/Robotweax/gnu-radio-srt) · [Install](https://github.com/Robotweax/gnu-radio-srt/blob/main/docs/install.md) · [Examples](https://github.com/Robotweax/gnu-radio-srt/tree/main/examples) · [Limitations](https://github.com/Robotweax/gnu-radio-srt/blob/main/docs/limitations.md)

### ROS 2 for robotics

The **ROS 2 SRT Bridge** provides a C++20 SDK and ROS 2 Jazzy packages for IMU and joint-state telemetry and durable measurement-rate commands. Telemetry uses freshness checks and latest-sample queues; commands use a persistent journal and recovery checks.

Acceptance is limited to the documented simulator builds. Physical-robot safety, production WAN behavior and hard real-time control are outside that scope.

[Source](https://github.com/Robotweax/ros-2-srt-bridge) · [Build guide](https://github.com/Robotweax/ros-2-srt-bridge/blob/main/docs/BUILDING.md) · [Architecture](https://github.com/Robotweax/ros-2-srt-bridge/blob/main/ARCHITECTURE.md) · [Evidence and limits](https://github.com/Robotweax/ros-2-srt-bridge/blob/main/M3_SCOPED_ACCEPTANCE.md)

### Intelligent Media Fabric

Research into SRT over secure mesh networks for professional contribution media. The project publishes experiment contracts, retained evidence and architectural decisions, including work on stream recovery and continuity when a transit node fails.

Pre-alpha research. It does not define a released product or a performance commitment.

[Source](https://github.com/Robotweax/Intelligent_Media_Fabric) · [Documentation](https://github.com/Robotweax/Intelligent_Media_Fabric/blob/main/docs/README.md) · [Qualification gates](https://github.com/Robotweax/Intelligent_Media_Fabric/blob/main/docs/qualification/gate-registry.md)

### Technical feedback and engineering enquiries

For bugs and technical feedback, use the relevant project's issue tracker and include the version, platform and steps to reproduce the problem. Consult each repository's contribution guidance before submitting changes.

For integration work and engineering enquiries: **[info@robotweax.ai](mailto:info@robotweax.ai)**.

[Website](https://robotweax.ai/en/) · [Deutsch](https://robotweax.ai/de/) · [LinkedIn](https://www.linkedin.com/company/robotweax/)
