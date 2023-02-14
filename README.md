
![image](https://user-images.githubusercontent.com/7415686/218782374-b28af1e5-0fec-446f-acd3-3ab5f3c17574.png)

# Wavedrom_Snippets

Wavedrom is a digital signal timing diagram generation tool.  It uses JSON markup and renders the graphic in a web browser.

This is an effective tool for generating timing diagrams for FUB signals and state transitions.  Unfortunately it is digital only, so velocity/position/acceleration waveforms are not possible.

This repo is for saving snippets I've used in the past (sharing or my future reference).  

## Documentation




Wavedrom JSON Markup Documentation: https://github.com/wavedrom/schema/blob/master/WaveJSON.md

Wavedrom Tutorial: https://wavedrom.com/tutorial.html

Wavedrom Editor: https://wavedrom.com/editor.html

## Usage/Examples

![image](https://user-images.githubusercontent.com/7415686/218812775-61f46b49-9be5-488a-b878-cb78be2acf6b.png)


```
{ signal: [
  { name: "Power",           wave: "01................" },
  { name: "Power On",        wave: "0.1..............." },
  { name: "Spin",            wave: "0...1............." },
  { name: "Spinning",        wave: "0....1............" },
  { name: "Offset",          wave: "0.....1....0..1..." },
  { name: "Offset Dir",      wave: "0.....1.......0..." },
  { name: "Adjust Done",     wave: "0.......1..0....1." },
  { name: "Coupling InSync", wave: "0....1............" },
  { name: "Slave State",     wave: "=.=..=............", 		data: ["Disabled", "Standstill", "Synchronized Motion", ] }
]}
```
