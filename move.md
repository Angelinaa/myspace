# myspace
function move()
{
	for(var i=0;i<fish.length;i++)
	{
		fish[i].x=fish[i].x+fish[i].speed*Math.cos(fish[i].div);
		fish[i].y=fish[i].y+fish[i].speed*Math.sin(fish[i].div);
	}
	myfish.x=myfish.x+myfish.speed*Math.cos(myfish.div);
	myfish.y=myfish.y+myfish.speed*Math.sin(myfish.div);
}
