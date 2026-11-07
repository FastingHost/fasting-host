# How to choose a VPS for your project

[Back to README](README.md) · [Plans and upgrades](PLANS-AND-UPGRADES.md) · [Official VPS buyer guide](https://fasting.host/vps-guide)

A useful VPS choice starts with the software you need to run. Write down its OS requirements, memory recommendation, working data size and expected busy periods before choosing a plan.

## 1. Decide how much server control you need

Choose **cPanel hosting** for a compatible website when you want website, database and email tools in a control panel. Choose a **VPS** when your project needs its own OS environment, server applications, custom web stack or game-server software.

A VPS gives you control and responsibility. Budget time for updates, firewall rules, monitoring, application maintenance and recovery. A working server is only the beginning of operating a reliable application.

## 2. Size the resources around the workload

| Resource | What to consider | What to measure after launch |
| --- | --- | --- |
| CPU | Application runtime, concurrent tasks, worker count and single-thread requirements. | Busy-period CPU use, request duration and processing queues. |
| Memory | OS, application workers, databases, caches and simultaneous users. | Peak use, swapping, memory pressure and out-of-memory failures. |
| Storage | OS, databases, uploads, updates, logs and temporary files. | Free space, growth rate, database size and log accumulation. |
| Network | User location, download size, request patterns and protocols. | Latency from actual users, packet loss and application response times. |

Traffic alone does not determine a server size. Two sites with the same visitor count can have very different requirements because of caching, database queries, plugins, media and background work. Start from the application's recommendations, leave operating headroom and measure a representative workload.

## 3. Compare the two Fasting Host ranges

**Privacy Cloud VPS** is the flagship privacy-first range in Amsterdam. **Performance Cloud VPS** runs in Eygelshoven and includes PLETX protection. Both support websites, applications, business projects and communities; compare their actual resources and upgrade prices.

The nearest geographic location is not always the best route for every visitor. If latency matters, test from the countries and networks your audience uses. Neither a datacenter name nor an uplink speed proves the response time of your particular application.

## 4. Choose an eligible operating system

Check your application's supported OS before choosing a template. The live checkout determines which OS choices are available for the selected family and plan.

- Nano plans currently list Debian 12 and 13.
- Windows choices start at Privacy VPS Plus or Performance VPS Basic.
- Other Linux and FreeBSD choices depend on the selected configuration.
- Linux/FreeBSD use root access; Windows uses Administrator access.
- An SSH public key is optional.

Do not select an OS only because it has the lowest idle memory usage. Application compatibility, security updates and your ability to maintain it matter more over the lifetime of the server.

## 5. Plan for growth

The standard resource selectors add up to 15 CPU units and 15 GB RAM above the base plan. Storage additions are separately listed. Larger requirements can be quoted individually.

Before a storage change, establish a recovery plan and check how the guest OS handles disk expansion. Additional virtual disk capacity may still require partition or filesystem expansion inside the guest. Do not assume that shrinking a plan or disk is equally straightforward.

## 6. Prepare a sensible operating checklist

1. Keep OS and application packages supported and updated.
2. Expose only the services your application needs.
3. Protect administrator accounts and recovery methods.
4. Monitor availability, resource use, disk space and important application errors.
5. Keep an independent backup and test restoration before relying on it.
6. Check an actual user journey, including HTTPS and any transactional emails.

DDoS protection is a network defence; it does not replace OS patching, secure application code or backups.

## Ask for a recommendation

Send your software name/version, required OS, expected audience, current resource use, storage growth and budget through the [contact page](https://fasting.host/contact). If this is an existing project, measured busy-period data is more useful than a visitor estimate alone.
