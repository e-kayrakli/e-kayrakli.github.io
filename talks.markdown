---
layout: talks
title: Talks    
slug: /talks
---

I enjoy preparing and giving talks about my work. So, here's a page specifically
for the talks I gave with short description and available materials for them, if
any. A more concise version of this list also exist in my [CV](cv).

Please contact me if you want to set up a talk in your institution or company
about my work on Chapel and Arkouda.

<br/>

{% include talk.html
    what="Scalable Parallel Programming with Chapel: From Multicore CPUs to
          GPU-Powered Supercomputers (a.k.a What Chapel Users Get Done and How)"
    date="October 15, 2025"
    where="LUMI User Coffee Breaks"
    slides="https://chapel-lang.org/presentations/EnginLUMI2025.pdf"
    video="https://lumi-supercomputer.github.io/LUMI-training-materials/User-Coffee-Breaks/20251015-user-coffee-break-Chapel/"
    desc="In this one, I wanted to focus on some of the accomplishments of
          Chapel users to motivate the language, rather than its syntax, though
          I covered some of the key features as well. The key message was that
          Chapel makes the path from a laptop to a supercomputer much easier"
%}

{% include talk.html
    what="Chapel's Batteries-Included Approach for Portable Parallel Programming"
    date="June 18, 2025"
    where="Los Alamos National Laboratory - Advances in Applied Computer Science Invited Speaker Series"
    slides="https://chapel-lang.org/presentations/EnginLANL2025.pdf"
    desc="How Chapel can be used to program most common parallel architectures,
    using the same set of first-class language featuers. Includes code examples,
    benchmark results and user stories"
%}

{% include talk.html
    what="High-Performance, Productive Programming using Chapel with Examples
          from the CFD Solver CHAMPS"
    date="February 20, 2025"
    where="NASA Ames Research Center"
    slides="https://chapel-lang.org/presentations/Chapel-CHAMPS-NASA2025.pdf"
    video="https://www.nas.nasa.gov/pubs/ams/2025/02-20-25.html"
    desc="This is a joint talk with our colleagues Eric Laurendeau and Karim
          Zayni from Polytechnique Montreal. We covered what Chapel is and how
          it helps CHAMPS team to build their CFD solver"
%}

{% include talk.html
    what="The Chapel Parallel Programming Language and its Ecosystem"
    date="October 4, 2024"
    where="HPE Inner Sourcing Summit II"
    slides="https://chapel-lang.org/presentations/EnginJadeInnerSourcing2024-public.pdf"
    desc="In this talk that was internal to HPE, we discussed ways in which
    fellow HPE employees can contribute to the Chapel ecosystem. As Chapel is an
    open-source language, the content of the talk did not include much
    proprietary discussion. The slides that are available above were only
    lightly edited before making them public."
%}

{% include talk.html
    what="Vendor-Neutral GPU Programming in Chapel"
    date="July 31, 2024"
    where="HPE Developer Meetup"
    slides="https://chapel-lang.org/presentations/HPEDevMeetup2024-GPUs.pdf"
    video="https://www.youtube.com/watch?v=nj-WqhGEy24&list=PLuqM5RJ2KYFin_PkkaAJWJF1KjcVGnagh&index=2"
    desc="A joint effort with my colleague Jade Abraham. I talked about Chapel's
          vendor-neutral GPU programming support, and Jade gave a live demo"
%}

{% include talk.html
    what="Making Parallel Programming and GPUs More Accessible with Chapel"
    date="May 31, 2024"
    where="AMD Developer Sync"
    slides="https://chapel-lang.org/presentations/EnginAMD2024-static-public.pdf"
    desc="I was invited to give a talk at this internal AMD event. One of the
    more in-depth technical discussions on Chapel's GPU support"
%}

{% include talk.html
    what="High-level, Vendor-Neutral GPU Programming Using Chapel"
    date="January 9, 2024"
    where="HPE Tech Talks"
    slides="https://chapel-lang.org/presentations/EnginTechTalk2024-static-public.pdf"
    desc="This is an internal HPE talk. A slightly earlier version of the talk I
    gave at AMD couple of months later"
%}

{% include talk.html
    what="Generating GPU Kernels from Chapel's Features for Parallelism and Locality"
    date="February 26, 2022"
    where="SIAM PP22 Minisymp. on Code Gen. and Transformation in HPC on Heterogeneous Platforms"
    slides="https://chapel-lang.org/presentations/Engin-SIAM-PP22-GPU-static.pdf"
    desc="Quite possibly, the earliest talk I gave on Chapel's GPU support. I am
    not sure whether at that point we had a full-blown runtime implementation.
    Luckily, this is a code generation venue, and the talk is more about how the
    Chapel compiler automatically generates GPU kernels from regular
    data-parallel loops in Chapel."
%}

<br />
