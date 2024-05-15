# The Unige Clusters: Baobab, Yggdrasil, and Bamboo (WIP)

The University of Geneva hosts and manages three computing clusters, two of which are (at the time of this writing) available to everyone to use:
 - Baobab, the largest cluster.
   - Baobab is hosted at Uni Dufour, the primary admin center of Unige, and has the largest number of computing resources (CPU and GPU alike) available
 - Yggdrasil, the astronomy cluster (open to all use however)
   - Yggdrasil is hosted near Versoix and is a smaller cluster with fewer CPU and GPU resources. Data between Baobab and Yggdrasil is not synced.
 - Bamboo, the planned cluster
   - Bamboo has been in the works for several years and should be online soon-ish, and will host additional capacity at Biotech. It's currently not clear whether This will replace Baobab or not, but the plan seems to be yes.
  
## How clusters work

In general a compute cluster can be thought of as a big herd of individual computers. Clusters often have 500+ "Nodes", which are actually rack-based computers something like this:

**IMAGE GOES HERE**

where many computers occupy a common rack, and are all connected to a central file system.

Nodes in a cluster, i.e. individual machines, may not always have the same hardware (number of CPUs, RAM, GPU, etc.) but are all accessible through the cluster system. As part of requesting resources on the cluster you can often specifcy exactly what you want.

