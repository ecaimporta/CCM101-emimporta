# Mission Reflection

This laboratory activity helped me understand why a photo-sharing application can benefit from Object Storage. If millions of photos were stored only on a traditional block storage hard drive, managing and expanding the storage could become difficult. Object Storage is designed for large amounts of unstructured data, so photos can be handled as individual objects and stored in a system made for this type of workload.

Docker also simplified the MinIO deployment. Instead of manually installing every part of the storage server, I was able to provide the required settings through a Docker command. The container name, ports, login information, and MinIO server configuration were included when the container was started. This made the deployment process easier to follow.

A bucket in Object Storage acts as a place where objects can be stored and organized. In this activity, I created the `client-photos` bucket and uploaded a sample file. Seeing the uploaded object inside the bucket helped me understand the concept better because I was able to perform the process myself.

For large companies, relying on a single physical machine would create a risk if that machine stopped working. Redundancy can help by keeping copies of important data on multiple systems or locations. Backup and replication strategies can also help organizations maintain access to their data when hardware problems happen.

My confidence with the Linux command line is gradually improving. I still need to carefully read commands and their output, but I am becoming more familiar with using Git, navigating directories, and working with Docker. This activity also showed me the importance of checking errors when a command does not work instead of assuming that the entire activity has failed.
