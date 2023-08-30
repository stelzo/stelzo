Moin 👋

I am a software engineer with a passion for mobile robotics and server development. While Rust, Golang are my favorite languages right now, I also have experience with Swift, C, C++, CUDA, Python, Java, PHP, SQL, and JavaScript. I am currently working on my master's thesis in reinforcement learning for autonomous exploration and will soon finish my computer science degree with a focus on AI.

## Robotics

- -WIP- [jlio](https://github.com/stelzo/jlio) [<a href="https://developer.nvidia.com/cuda-toolkit"><img height=12 align="center" src="images/cudaIcon.png" /></a>]: GPU accelerated LiDAR odometry for the NVIDIA Jetson SoC
- [ros_pointcloud2](https://github.com/stelzo/ros_pointcloud2) [<a href="https://www.rust-lang.org"><img height=14 align="center" src="images/rustIcon.png" /></a>]: safe on-the-fly point cloud message conversions for ROS 1 and ROS 2
- [cupcl-rs](https://github.com/stelzo/cupcl-rs) [<a href="https://www.rust-lang.org"><img height=14 align="center" src="images/rustIcon.png" /></a>, <a href="https://developer.nvidia.com/cuda-toolkit"><img height=12 align="center" src="images/cudaIcon.png" /></a>]: Rust bindings for [cuPCL](https://github.com/NVIDIA-AI-IOT/cuPCL) and additional custom GPU filters
- [cloudfilter](https://github.com/stelzo/cloudfilter) [<a href="https://www.rust-lang.org"><img height=14 align="center" src="images/rustIcon.png" /></a>]: A passthrough demo using the ros_pointcloud2 crate and CUDA filters
- [flysense-viewer](https://github.com/stelzo/flysense-viewer) [<a href="https://cplusplus.com"><img height=12 align="center" src="images/cppIcon.png" /></a>]: Drone state visualization overlay streamed to HDMI OpenCV ([paper](https://dl.acm.org/doi/abs/10.1145/3579170.3579266))
- [flysense-jetson-cam](https://github.com/stelzo/flysense-jetson-cam) [<a href="https://cplusplus.com"><img height=12 align="center" src="images/cppIcon.png" /></a>, <a href="https://developer.nvidia.com/cuda-toolkit"><img height=12 align="center" src="images/cudaIcon.png" /></a>]: A Simple camera streaming application for the NVIDIA Jetson with GStreamer and OpenCV ([paper](https://dl.acm.org/doi/abs/10.1145/3579170.3579266))


## Web
- [tablecompare.com](https://tablecompare.com) [<a href="https://angular.io"><img height=15 align="center" src="images/angularIcon.png" /></a>, <a href="https://developer.mozilla.org"><img height=15 align="center" src="images/htmlIcon.png" /></a>, <a href="https://developer.mozilla.org"><img height=15 align="center" src="images/cssIcon.png" /></a>, <a href="https://cplusplus.com"><img height=12 align="center" src="images/cppIcon.png" /></a>]: A web app to compare tables with typesafe similarity running in the browser with  WebAssembly
- [openapi-api-version-print](https://github.com/stelzo/openapi-api-version-print) [<a href="https://go.dev"><img height=8 align="center" src="images/goIcon.png" /></a>]: GitHub action to parse and output the API version of an OpenAPI spec

### dofusdude
A namespace for my tools and APIs helping the [Dofus](https://www.dofus.com) developer community.

- [doduda](https://github.com/dofusdude/doduda) [<a href="https://go.dev"><img height=8 align="center" src="images/goIcon.png" /></a>]: CLI with basic TUI using the Launcher flatbuffer APIs to download games and make them usable for applications
- [doduapi](https://github.com/dofusdude/doduapi) [<a href="https://go.dev"><img height=8 align="center" src="images/goIcon.png" /></a>]: RESTful API for the Dofus encyclopedia using GitHub Action chains and doduda
- [ankama-discord-hooks](https://github.com/dofusdude/ankama-discord-hooks) [<a href="https://go.dev"><img height=8 align="center" src="images/goIcon.png" /></a>, <a href="https://developer.mozilla.org"><img height=15 align="center" src="images/jsIcon.png" /></a>, <a href="https://developer.mozilla.org"><img height=15 align="center" src="images/htmlIcon.png" /></a>, <a href="https://developer.mozilla.org"><img height=15 align="center" src="images/cssIcon.png" /></a>]: Public Discord Webhooks CRUD API for updates related to the Ankama Kosmos using a generated SDK with [WebUI](https://discord.dofusdude.com)
- [almanax-api](https://github.com/dofusdude/almanax-api) [<a href="https://www.java.com/de/"><img height=23 align="center" src="images/javaIcon.png" /></a>]: Restful API for curating daily bonuses and serving it to other services ([examples](https://github.com/dofusdude/almanax-api#awesome-projects-using-the-api))
- [almanax-scraper](https://github.com/dofusdude/almanax-scraper) [<a href="https://www.python.org"><img height=15 align="center" src="images/pythonIcon.png" /></a>]: Whitelisted web scraper for the Dofus Almanax API
- [api-docs](https://github.com/dofusdude/api-docs) [OpenAPI, GitHub Actions]: OpenAPI spec for all APIs with CI/CD for generating and publishing 5 SDKs on push
