VDMS is a storage solution for efficient access of big-”visual”-data that aims
to achieve cloud scale by searching for relevant visual data via visual
metadata stored as a graph and enabling machine friendly enhancements to
visual data for faster access.  We use an in-persistent-memory graph database
developed in our team called Persistent Memory Graph Database (PMGD) as the
metadata tier and we are exploring the use of an array data manager, TileDB
and other formats for images, visual descriptors, and videos as part of our
Visual Compute Library (VCL). VDMS is run as a server listening for client
requests and we provide client side bindings to enable communication between (
python, C++) applications and the server. Hence, it also has a Request Server
component defined to implement the VDMS API, handle concurrent client
requests, and coordinate the request execution across its metadata and data
components to return unified responses. This project aims to research the use
of a scalable multi-node graph based metadata store as part of a hierarchical
storage framework specifically aimed at processing visual data, and also it
includes an investigation into the right hardware and software optimizations
to store and efficiently access large scale (pre-processed) visual data.


## Get Started

To get started, take a look at the [INSTALL.md](INSTALL.md) file, where
you will find instructions on how to install and run the server.

Also, visit our [wiki](https://github.com/IntelLabs/vdms/wiki)
to learn more about the VDMS API, and take a look at some of
the examples/tutorials.

## Note
This project is forked from the public VDMS repo and develops an asynchronous architecture for the same.
