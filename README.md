# visimLab
visimLab project is intended to be a free solution for the control system, targeting to save not only money, but also engineering effort for the development.

[below is the plan]
* visual: a group of HMI components
  * sketch: graphical programming tool, also serves as drawing tool
  * capture: software oscillator scope to capture waveforms 
  * live: HMI editor and components
* simulator: simulate the program
* embedded: a group of system services for the embedded software development
  * varMgr: variable management service 
  * parmMgr: parameter management service :
  * diagMgr: diagnostics management service
  * rte: runtime time environment
  * fastRte: a express version of runtime time environment, which is intended for fast real time application
* link: data link between machines
  * fsl: framed series link between machines
  * csl: continuous series link between machines, usually used for strict real time application
* connection: machine's external interface for communication
  * opc ua: 
* machine: 
