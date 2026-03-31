# LuckyTurtle Harbor 🐢

**Multi-Coin Solo Mining Harbor**

LuckyTurtle Harbor is a multi-coin solo mining platform built for both small and large miners.  
It provides dedicated lanes for tiny devices and high-power ASICs with real-time stats and transparent operation.

---

## 🌐 Website
https://luckyturtle.io

---

## ⚙️ Features

- 🐢 Solo mining (no shared pool payouts)
- ⚡ Multi-coin support
- 🔌 Dedicated ports for tiny + ASIC miners
- 🌍 Global + EU endpoints
- 📊 Live Harbor stats
- 💰 0.5% Harbor Fee

---

## ⛏️ Supported Coins

| Coin | Algorithm | Ports |
|------|----------|------|
| DigiByte (DGB) | SHA256d | 4033 / 4035 |
| Bitcoin (BTC) | SHA256d | 4333 / 4335 |
| Bitcoin Cash (BCH) | SHA256d | 6033 / 6035 |
| Bitcoin Silver (BTCS) | SHA256d | 7033 / 7035 |

---

## 🔌 Connection Examples

### DigiByte (ASIC)
```
stratum+tcp://luckyturtle.io:4033
```

### DigiByte (Tiny)
```
stratum+tcp://luckyturtle.io:4035
```

### Bitcoin (ASIC)
```
stratum+tcp://luckyturtle.io:4333
```

---

## 🌍 EU Endpoints

Replace hostname with:
```
eu.luckyturtle.io
```

---

## 📊 API

```
https://luckyturtle.io/api/stats
```

---

## 🧠 Notes

- DigiByte is a multi-algorithm chain — this harbor supports the SHA256d lane
- Designed for compatibility across miner types and firmware
- Built on LuckyTurtleStratum backend

---

## 🚀 Status

Active and accepting miners.

---

## 📄 Additional Info

- Pool summary: [pools.md](pools.md)  
- Connection guide: [connect.md](connect.md)  
- Listing data: [listing.json](listing.json)
