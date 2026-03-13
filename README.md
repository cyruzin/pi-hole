# Pi-hole + Unbound on Raspberry Pi

![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)
![Pi-hole](https://img.shields.io/badge/pi--hole-%2396060c.svg?style=for-the-badge&logo=pi-hole&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

Optimized configuration to run **Pi-hole** as a network-wide ad blocker and **Unbound** as a local recursive DNS resolver, enhancing both privacy and performance.

---

## Getting Started

Ensure you are in the directory containing your `docker-compose.yml` file and run:

```bash
docker compose up -d
```

## Updating Images

To update to the latest versions of Pi-hole and Unbound without losing your configurations:

```bash
docker compose pull && docker compose up -d
```

**Note**: Data is persisted in `./etc-pihole` and `./unbound` directories.
