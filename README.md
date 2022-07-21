:warning: **Status: gathering requirements** :warning

---

# ssb-meta-feed-group-spec
_working title_

## Problem

We want to put different group content in different sub-feeds, in order to support more partial replication.

But we need have a clear way to discover how you've been invited to a group without replicating the whole group's data.

We also need to consider how to ensure our group data is replicated _enough_ - e.g. if a group is just me and my sister, then are there gonna be enough copies of the group data to be resilent/ timely.


--- 

Existing work to be ported in:
1. [2022-06-02 meeting](./2022-06-02-notes.md) - has good steps for how discovery works
2. [2022-07-06 meeting](./2022-07-06-notes.md)
