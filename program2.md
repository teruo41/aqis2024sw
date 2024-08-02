<style type="text/css">
  thead {
    display: none;
  }
  table, td {
    border: none;
  }  
</style>

# AQIS2024 satellite workshop program
{:style="display: none;"}

## Detailed Program

| time  | program         |
|-------|-----------------|
|  9:50 | Opening remarks |
| 10:00 | Invited talk 1 - __Thinh Le__ (University of Technology Sydney)<br><br>___Full-stack quantum computing for quantum advantage___<br>Quantum computing promises superior advantage compared to classical computing in specific instances. Identifying these instances is currently an active topic of research encapsulating a wide variety of disciplines such as quantum algorithm, complexity theory, compilation, resource estimation, hardware and architecture design. In this talk, I will overview the complete stack of quantum computing from algorithms to hardwares, then detail the design of a compilation and resource computation software platform at QSI UTS. Our platform is built on the concept of quantum algorithm on graph state in the style of measurement-based quantum computation. Various levels of optimisation in our compilation pipeline allow to minimise resources such as space, time or spacetime volume leading to efficient execution of quantum algorithms. Our software can be used to help identify quantum advantages and efficient hardware architecture designs.|
| 10:40 | Invited talk 2 - __Poulami Das__ (The University of Texas at Austin)<br><br>___Architectures for enabling real-time quantum error correction___<br>The error rates of quantum hardware far exceed what can be tolerated at the application-level. This causes computational errors during program execution and limits us from running most practical quantum algorithms. Quantum error correction (QEC) bridges this gap by encoding fault-tolerant logical qubits using redundant physical qubits (deemed as the size of the code) and correcting errors in real-time as they occur. In this talk, I will describe the role of software and architecture in improving the performance of QEC and provide an overview of my contributions in these areas. I will describe the challenges in enabling real-time QEC within a budget of a few microseconds and discuss LILLIPUT, a lightweight reconfigurable practical lookup table decoder for identifying errors on small QEC codes. Then, I will discuss Astrea and Promatch which are fixed-function accelerator designs for correcting slightly larger codes as compared to LILLIPUT. These solutions rely on hardware-accelerated greedy search for identifying corrections. Next, I will discuss the AFS decoder which focuses on the system-level architecture and organization of decoders in large-scale fault-tolerant systems. The AFS decoder enables contention-aware sharing of decoding resources across the system to improve the hardware efficiency of the design. Finally, I will conclude with my future research vision towards building fault-tolerant systems, designing the architecture stack as quantum computers scale, and exploring other areas in computing, such as cryogenic systems.|
| 11:20 | Break           |
| 11:40 | Invited talk 3 - __Ting-Chun Lin__ (University of California San Diego)<br><br>___Quantum codes and fault tolerance___<br>One of the recent breakthroughs in quantum error correction is the construction of quantum Low-Density Parity-Check (qLDPC) codes. These codes are notable for their high rates and large distances, which we will explore in the first half of the talk.<br>While these qLDPC codes can be used for certain fault-tolerant schemes, the codes are not "natively fault-tolerant". This means that these fault-tolerant schemes require quantum information to be moved in and out of these codes during computation, resulting in additional overhead.<br>In the second half of the talk, we will discuss a common strategy for achieving "native fault tolerance" in qLDPC codes by finding codes that support transversal non-Clifford gates. We will highlight some potential constructions and the challenges they face. Additionally, we will remark on other approaches to achieve fault tolerance beyond the framework of stabilizer codes.|
| 12:20 | Lunch           |
| 13:40 | Poster session  |
| 14:40 | Invited talk 4 - __Shin Nishio__ (Okinawa Institute of Science and Technology Graduate University)<br><br>___TBA___<br>TBA.|
| 15:20 | Invited talk 5 - __Warit Asavanant__ (The University of Tokyo)<br><br>___Advances toward large-scale fault-tolerant optical quantum computing with quantum teleportation___<br>Since its proposal, we have seen developments of quantum computing platforms across various physical systems. To achieve useful quantum computation, we must scale up the system so that a large number of qubits can be utilized for both calculations and achieving fault tolerance. Scalability, however, is not a straightforward task; for most systems, we cannot simply put multiple copies of the small-scale systems due to physical, technical, and practical limitations. In this regard, optical systems have utilized their physical traits as flying qubits with high carrier frequency to achieve large-scale quantum entanglement and computation, without requiring more physical components. This removes most of the hurdles found in other systems. In this talk, I will discuss the approaches taken by optical systems in the journey for large-scale quantum computation. The key technology here is the quantum teleportation protocol which contains all the basic ingredients required in the fault-tolerant quantum computation. This talk will review developments of optical quantum computation with main focus on continuous-variable (CV) systems and multiplexing techniques which have shown to be most prominent in CV optical systems.|
| 16:00 | Break           |
| 16:10 | Panel session   |
| 16:50 | Closing remarks |

## Evening Networking Event

We will hold an evening networking event from __18:00__.
If you want to join, please mark the checkbox in [the registration application](https://forms.office.com/r/aBzvTxyC93) by Aug. 10.
The cost will be 6,000 JPY (around $40); please pay at the place.

Sapporo Beer Garden, Poplar-kan  
9-2-10, Kita7Jo, Higashi-ku, Sapporo, Hokkaido, 065-0007  
[https://www.sapporo-bier-garten.jp/global/english.html](https://www.sapporo-bier-garten.jp/global/english.html)  
This place is 15 minutes by foot and bus or 30 minutes by foot from the venue.  

{% raw %}
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2060.974969491864!2d141.36699899196162!3d43.069644141417825!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f0b296e9f8921d9%3A0xab7036fea64b2cd2!2z44Od44OX44Op6aSo!5e0!3m2!1sen!2sjp!4v1722235920871!5m2!1sen!2sjp" width="600" height="350" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
{% endraw %}

Back to [Home]({{ site.baseurl }})
