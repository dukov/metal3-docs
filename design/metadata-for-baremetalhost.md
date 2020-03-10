<!--
 This work is licensed under a Creative Commons Attribution 3.0
 Unported License.

 http://creativecommons.org/licenses/by/3.0/legalcode
-->

# metadata-for-baremetalhost

## Status

One of: provisional|implementable|implemented|deferred|rejected|withdrawn|replaced

## Table of Contents

[Tools for generating][] a table of contents from markdown are available.

<!--ts-->
   * [metadata-for-baremetalhost](#metadata-for-baremetalhost)
      * [Status](#status)
      * [Table of Contents](#table-of-contents)
      * [Summary](#summary)
      * [Motivation](#motivation)
         * [Goals](#goals)
         * [Non-Goals](#non-goals)
      * [Proposal](#proposal)
         * [Implementation Details/Notes/Constraints [optional]](#implementation-detailsnotesconstraints-optional)
         * [Risks and Mitigations](#risks-and-mitigations)
      * [Design Details](#design-details)
         * [Work Items](#work-items)
         * [Dependencies](#dependencies)
         * [Test Plan](#test-plan)
         * [Upgrade / Downgrade Strategy](#upgrade--downgrade-strategy)
         * [Version Skew Strategy](#version-skew-strategy)
      * [Drawbacks [optional]](#drawbacks-optional)
      * [Alternatives [optional]](#alternatives-optional)
      * [References](#references)

<!-- Added by: stack, at: 2019-02-15T11:41-05:00 -->

<!--te-->

[Tools for generating]: https://github.com/ekalinin/github-markdown-toc

## Summary



## Motivation

Ability to pass User Data (i.e. software configurations settings) and
Network Data have been implemented and supported atleast by Ironic
provosioner. The only part of configuration parameters which can be
assigned to host are vendor or provisioner implementation specific (e.g.
instance uuid for Ironic and cloud-init)

### Goals

List the specific goals of the design.
How will we know that this has succeeded?

### Non-Goals

What is out of scope for this design?
Listing non-goals helps to focus discussion and make progress.

## Proposal

This is where we get down to the details of what the proposal actually is.

### User Stories [optional]

Detail the things that people will be able to do if the design is
implemented.  Include as much detail as possible so that people can
understand the "how" of the system.  The goal here is to make this
feel real for users without getting bogged down.

#### Story 1

#### Story 2

### Implementation Details/Notes/Constraints [optional]

- What are the caveats to the implementation?
- What are some important details that didn't come across above.
- Go in to as much detail as necessary here.
- This might be a good place to talk about core concepts and how they relate.

### Risks and Mitigations

What are the risks of this proposal and how do we mitigate.  Think
broadly.  For example, consider both security and how this will impact
the larger kubernetes ecosystem.

## Design Details

- What will actually need to change in the code?
- What new objects is this going to require?
- What new fields are needed, for either the Spec or Status section?
- What other changes (labels, annotations, etc.) are needed?

### Work Items

Work items or tasks -- break the feature up into the things that need to be
done to implement it.

### Dependencies

* Include specific references to work here or in other projects that
  this design either depends on or is related to.

* Does this feature require any new library dependencies or code
  otherwise not included in the code? Or does it depend on a specific
  version of library?

### Test Plan

Consider the following in developing a test plan for this enhancement:

- Will there be end-to-end and integration tests, in addition to unit
  tests?
- How will it be tested in isolation vs. with other components?

No need to outline all of the test cases, just the general strategy.

Anything that would count as tricky in the implementation and anything
particularly challenging to test should be called out.

All code is expected to have adequate tests.

### Upgrade / Downgrade Strategy

If applicable, how will the component be upgraded and downgraded? Make
sure this is in the test plan.

Consider the following in developing an upgrade/downgrade strategy for
this enhancement:

- What changes (in invocations, configurations, API use, etc.) is an
  existing cluster required to make on upgrade in order to keep
  previous behavior?
- What changes (in invocations, configurations, API use, etc.) is an
  existing cluster required to make on upgrade in order to make use of
  the enhancement?

### Version Skew Strategy

If applicable, how will the component handle version skew with other
components? What are the guarantees? Make sure this is in the test
plan.

## Drawbacks [optional]

Why should this design _not_ be implemented.

## Alternatives [optional]

Similar to the `Drawbacks` section the `Alternatives` section is used
to highlight and record other possible approaches to delivering the
value proposed by a design.

## References

Please add any useful references here. You are not required to have any
reference. Moreover, this specification should still make sense when your
references are unavailable. Examples of what you could include are:

- Links to mailing list or other discussions
- Links to relevant research, if appropriate
- Related designs, as appropriate
- Anything else you feel it is worthwhile to refer to
