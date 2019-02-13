# Bapp
The base app of the Election system to connect all the services get-together and deploy as a one system. 

**Folder structure**

```bash
├── Apps
│    ├── <app name>    
│    │       ├── <app content>
│    │       └── Dockerfile
├── Services
│    ├── <service pack name>
│    │       ├── <service name>
│    │                ├── <service content>
│    │                └── Dockerfile
│    │       
│    ├── Common
│    │       ├── <service pack name>
│    │                ├── <service name>
│    │                          ├── <service content>
│    │                          └── Dockerfile
│    │
└── Deployment

```

## Deployment Architecture

![alt text](https://github.com/ECLK/Bapp/blob/master/Deployment%20architecture%20v1.png)
