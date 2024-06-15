## Introduce

The At-Hub([@ Hub](https://github.com/At-EC/At-Hub)) repository is used to manage all ([@ EC](https://github.com/At-EC)) repositories and does not implement any functions of the code business logic itself, and the current supported repositories are shown in the following lists.

* **[At-RTOS](https://github.com/At-EC/At-RTOS)**: An open and user-friendly real-time operating system (RTOS) for the embedded controller (EC).
* **[At-FSM](https://github.com/At-EC/At-FSM)**: An open and user-friendly embedded Finite State Machine (FSM) included the Primitive State Machine (PSM) and Hierarchical State Machine (HSM).
* **[At-BSI](https://github.com/At-EC/At-BSI)**: An open and user-friendly board supported interface for the embedded controller peripheral compatibility.

## Usage

You can download and start to use it by the following instructions.

```shell
git clone https://github.com/At-EC/At-Hub.git
cd At-Hub
git submodule update --init --recursive
```

## License

The At-Hub is completely open-source, can be used in commercial applications for free, does not require the disclosure of code, and has no potential commercial risk. License information and copyright information can generally be seen at the beginning of the code:

```c
/**
 * Copyright (c) Riven Zheng (zhengheiot@gmail.com).
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
**/
```

The MIT License is [here](./LICENSE).
