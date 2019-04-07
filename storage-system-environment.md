# Storage System Environment

Storage is recognized as a distinct resource, requiring focus and specialization for implementation and management.

## 3 Main components of storage systems:

### 1. Host

#### Physical Components:

These components communicate with one another via _busses_. A _bus_ connects the CPU to other components.

1.  CPU

    Four main components:

    1.  **ALU**: Arithmetic Logical Unit

        -   performs mathmatic and logical operations (+, -, Boolean[`AND`, `OR`, `NOT` ])

    2.  **Control Unit**

        -   controls CPU operations

    3.  **Register**

        -   High-speed storage locations

        -   stores intermediate data that is required by CPU to perform instructions, providing fast access due to
            proximity to the CPU

    4.  **L1 cache**

        -   holds data and program instructions that are likely to be needed by the CPU in the near future.

        -   Slower than registers, but provides more storage

2.  Storage devices

    -   Memory

        -   RAM

            -   accesses any memory location and can have data written into or read from it.

            -   Volatile: requires constant power supply to maintain memory cell content. Data erased when power is interrupted

        -   ROM  

            -   Non-volatile, only allows data to be read from it. Holds data for internal routines like system startup

    -   Disks

        -   HDD (magnetic)

        -   CD-ROM or DVD-ROM (optical)

        -   Floppy disk (magnetic)

        -   Tape drive (magnetic)

3.  I/O devices

    1.  User to host communication

        -   Handled by basic I/O like keyboard, mouse, and monitor. Enable user to interact with data.

    2.  Host to host communication

        -   Enabled via NICs or modems

    3.  host to storage communication

        -   handled by _Host Bus Adapter_

            -   application-specific circuit (ASIC) board that performs I/O functions between host and Storage

            -   relieves CPU of additional I/O processing workload

            -   provide connectivity outlets (Ports) to connect host to storage

### 2. Connectivity

Interconnection between hosts or between a host and any other peripheral, such as printers or storage devices.

Components of connectivity in a storage system environment classified into _Physical_ and _Logical_

#### Main components of Connectivity:

1.  Bus

    -   a collection of paths that transmits data from one part of the computer to another, such as CPU to memory.

2.  Port

    -   specialized outlet enabling connectivity between the host and external devices

3.  Cable

    -   connect hosts to internal or external devices using copper or fiber optic media

### 3. Storage
