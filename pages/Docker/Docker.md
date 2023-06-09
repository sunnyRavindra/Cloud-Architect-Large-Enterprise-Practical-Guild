### Docker Client Server Architecture 
```mermaid
flowchart TD
Docker-Client --> Rest-API --> Docker-Host --> Docker-Demon 
Docker-Demon --> Docker-Images
Docker-Demon --> Docker-Containers
Docker-Registry --> Docker-Images
Docker-Images --> Docker-Containers 
```

![Docker Architecture diagram](https://docs.docker.com/assets/images/architecture.svg)
### My Docker Approach

- [[My Docker Approach]]

### Related Topics

- [[Chroot]]

- [[Linux Namespaces]]

- [[Docker DevEnv Setup]]

- [[Docker Nextjs Application]]

### References

- [Docker Overview](https://docs.docker.com/get-started/overview/)

- [Docker Quick Start Guide](https://docs.docker.com/get-started/overview/)

- [kernel namespaces and cgroups](https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504)

