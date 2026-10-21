# 1 Compilación

T1
```bash
cd /home/andres/minios-lab
make clean && make
```

# 2 Arranque 3 Componentes

### Bridge T2
```bash
cd /home/andres/minios-lab/bridge
node index.js
```

### DashBoard T3

```bash
cd /home/andres/minios-lab/dashboard
npm run dev
```

### MiniOS T1

```bash
cd /home/andres/minios-lab
./minios
```

# 3 Creacion 5 Procesos

### T1 MiniOS
```bash
run programs/bin/countdown 90
run programs/bin/countdown 90
run programs/bin/primos 200000
run programs/bin/primos 200000
run programs/bin/fibonacci 40
```

# 4 Dashboard Gantt 

Abrir http://localhost:5173

# 5 T1 MiniOS

```bash
ps
```

# 6 Cambio time Slice

```bash
slice 200
```

```bash
slice 1500
```

# 7 Kill

```bash
kill ###
ps
```

# 8 Stats

```bash
stats
```

# 9 Limpieza y sin zombies

```bash
exit
```
```bash
ps aux | grep defunct
```





