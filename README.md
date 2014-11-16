Hp-Bar-Code
===========
onClipEvent(enterFrame){
	this.xscale = _root.hp;
	if(_root.hp < 0){
		_root.hp = 0;
		_root.gotoAndPlay(2)
	}
}


//Actionscript 2.0 code for HP Bar
