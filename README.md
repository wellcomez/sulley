Sulley is a fuzzer development and fuzz testing framework consisting of multiple extensible components. Sulley (IMHO) exceeds the capabilities of most previously published fuzzing technologies, commercial and public domain. The goal of the framework is to simplify not only data representation but to simplify data transmission and target monitoring as well. Sulley is affectionately named after the creature from Monsters Inc., because, well, he is fuzzy.

Modern day fuzzers are, for the most part, solely focus on data generation. Sulley not only has impressive data generation but has taken this a step further and includes many other important aspects a modern fuzzer should provide. Sulley watches the network and methodically maintains records. Sulley instruments and monitors the health of the target, capable of reverting to a known good state using multiple methods. Sulley detects, tracks and categorizes detected faults. Sulley can fuzz in parallel, significantly increasing test speed. Sulley can automatically determine what unique sequence of test cases trigger faults. Sulley does all this, and more, automatically and without attendance.

Current Changelog:
    - Some internal changes to make it easier to go through the code
    - Setting up for the move from PyDBG to Invisig0th's VDB
