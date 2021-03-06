# brevis

brevis, a Second Generation artificial life simulator.

brevis is a revitalization of the spirit of the breve simulator in the functional
language, Clojure.
	
Documentation:   http://cs.brandeis.edu/~kyleh/brevis
Chat: #brevis@irc.freenode.net
  
by Kyle Harrington (kyleh@cs.brandeis.edu), 2011-2013.
   http://kyleharrington.com

## Getting started:

brevis is designed to be compatible with Eclipse and a couple of Eclipse addons. These instructions should work with Eclipse versions on all major OS platforms.

1. Install Eclipse - The development environment - http://www.eclipse.org/ 

2. Install the EGit addon for Eclipse - Version control -  http://www.eclipse.org/egit/

3. Install the CounterClockwise - Clojure support in Eclipse - http://code.google.com/p/counterclockwise/

4. Download brevis. Within Eclipse, Import Project->Team->Git URI, choose an address listed on https://github.com/kephale/brevis

5. One-time project configuration. Within Eclipse, right click on brevis (the project you just imported), choose Leiningen->Reset Project Configuration

## Usage

Developed for use with the Clojure Eclipse plugin, CounterClockwise (this must be installed).

1. Open brevis.example.swarm

2. Menu: Clojure -> Load file in REPL

## Controlling the simulation

Keyboard keys:

esc - kill the simulation  
<hold> z \& <hold> left button - rotate camera  
<hold> z \& <hold> right button - translate camera  
mouse wheel forward/backward - zoom camera   
p - pause  
o - screenshot  

## License

This file is part of brevis.                                                                                                                                                 
                                                                                                                                                                                     
    brevis is free software: you can redistribute it and/or modify                                                                                                           
    it under the terms of the GNU General Public License as published by                                                                                                             
    the Free Software Foundation, either version 3 of the License, or                                                                                                                
    (at your option) any later version.                                                                                                                                              
                                                                                                                                                                                     
    brevis is distributed in the hope that it will be useful,                                                                                                                
    but WITHOUT ANY WARRANTY; without even the implied warranty of                                                                                                                   
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the                                                                                                                    
    GNU General Public License for more details.                                                                                                                                     
                                                                                                                                                                                     
    You should have received a copy of the GNU General Public License                                                                                                                
    along with brevis.  If not, see <http://www.gnu.org/licenses/>.                                                                                                          
                                                                                                                                                                                     
Copyright 2012, 2013 Kyle Harrington