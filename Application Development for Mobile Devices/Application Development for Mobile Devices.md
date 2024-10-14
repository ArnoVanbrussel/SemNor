# 1 Android Platform/Architecture
- Software stack
- Several layers
- SDK - Software Developer Kit
- Lot's of online documentation
## 1.1 Software Stack
![[Pasted image 20241010083749.png]]
### 1.1.1 Application Layer
- System apps + User apps
- Contacts, Phone, Angry birds
- Not hard coded
### 1.1.2 API Framework
- Form building blocks to create android apps by simplifying the reuse of core, modular system components
- Reusable software
	- View system
	- Package manager
	- Window manager
	- Resource manager
	- Activity manager
		- High level
		- Application
		- helps coordinate and support navigations between user interfaces
### 1.1.3 System Libraries
- Native Libraries written in C or C++
- SQLite, SSL, OpenGL
- Handles lot of core performance sensitive activities
- Quickly rendering webpages, updating display
- Standard OS system calls
- Process and thread creation
- Playing back audio, video files
### 1.1.4 Android Runtime
- Two components
	- Core Libraries
	- ART Android Runtime
- Prior to API level 21
	- Core Java Libraries
	- Dalvik machine
### 1.1.5 Linux Kernel Layer
- Core services for device
- Generic OS services
- Permissions architecture
- Memory and Process management
- Security
- **Android specific:**
	- Power management
	- Low memory killer
	- Inter-Process Communication
### Why not JVM
- Android specific demands
	- Designed for resource-constrained environments
	- Slower CPU (mobile)
	- Less memory
	- Limited battery life
## Android Studio Bundle
- Android platform
- Android Studio IDE
- Development tools
- System image for emulator
