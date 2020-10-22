# TwoMegCoCo - an SRAM-based 2048kB RAM Expansion for the TANDY Color Computer 3
A TTL logic, SRAM-based 2048kB (2MB) memory expansion for the Color Computer 3.  Upper bank registers are write-only, like the older Disto units. All parts are through hole for easy hobbyist assembly.

## Motivation

After acquiring a used Disto 2MB memory expansion, I wondered if a similar 1980's TTL-based solution could have been created using SRAM (ignoring the fact that 2MB of SRAM was extremely expensive at the time compared to DRAM), and I wanted to see if I could design a unit using only off-the-shelf TTL circuitry. (And, since, at time of writing this, the MMU extension PCB is still being debugged, the question is yet unanswered :-)).

Obviously, as with the HalfMegCoco project, there is little economic incentive in this project, as the contemporary commercial solutions offer more functionality at a cheaper price.  But, there's always some value in building a unit oneself, or at least understanding how the MMU process works by inspecting the actual TTL logic.

## Status

Currently, the SRAM board has been confirmed to work with various MMU extension solutions (Boysontech/Cloud9), but I am still designing and debugging the MMU board (would appreciate help, if there is interest).



## License
Copyright (C) 2020  RETRO Innovations

These files are free designs; you can redistribute them and/or modify
them under the terms of the Creative Commons Attribution-ShareAlike 
4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

These files are distributed in the hope that they will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
license for more details.


