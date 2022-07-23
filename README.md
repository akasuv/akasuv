``` typescript
type Me<N, R, A, NK, T> = {  
    name: N;  
    role: R;    
    at: A;
    nickname: NK;
    tags: T;
 }
  
type Tags =   
| "⚡️ Frontend Enthusiast"  
| "🥷 TypeScript Ninja"  
| "🏎 Neovim Player"  
| "🤖 Bot Creator"  
| "👾 Solidity Newbie"  

Me<"Wei Su", "Frontend Dev", "CyberConnect", "SUV", Tags>

```
