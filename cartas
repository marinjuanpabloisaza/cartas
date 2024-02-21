// carta.js
let p=['♥','♦','♠','♣'],n=['2','3','4','5','6','7','8','9','10','J','Q','K','A'],r='',b=[0,0,0],j=[0,0,0];
for(let i=0;i<3;i++){
  const a=p[Math.floor(Math.random()*p.length)],
        o=n[Math.floor(Math.random()*n.length)],
        v=parseInt(o)||(o==='A'?11:10);
  b[i]=v;
  r+=`[${o} ${a}] `;
}
for(let i=0;i<Math.min(parseInt(`$(querystring)`),4)||1;i++){
  const a=p[Math.floor(Math.random()*p.length)],
        o=n[Math.floor(Math.random()*n.length)],
        v=parseInt(o)||(o==='A'?11:10);
  j[i]=v;
  r+=`[${o} ${a}] `;
}
`${r}Bot(${b.reduce((a,v)=>a+v,0)}) vs Jugador(${j.reduce((a,v)=>a+v,0)})|${j.every(v=>v>21)?'¡Perdiste! Jugador se pasó de 21.':b.every(v=>v>21)||j.reduce((a,v)=>v+a,0)>b.reduce((a,v)=>v+a,0)?'¡Ganaste!':'¡Perdiste! El bot está más cerca de 21.'}`
