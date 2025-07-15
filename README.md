# AIX Subnet Analytics (Bittensor)

📊 A research project tracking node activity, token holder growth, and economic rewards for the AIX subnet (Subnet 11) on Bittensor.

---

## 🧠 What This Tracks

- **Validator Infrastructure**: Daily AIX node count using the Bittensor Python client
- **Token Adoption**: AIX holder growth using the Etherscan API (Ethereum)
- **Economic Incentives**: TAO emission modeling and USD valuation via TaoStats and Dune

---

## 📂 Repo Structure

| Folder      | Contents                                     |
|-------------|----------------------------------------------|
| `data/`     | Daily CSV logs for nodes and holders         |
| `charts/`   | Visuals created from Python + Dune           |
| `notebooks/`| Jupyter notebooks from Google Colab          |

---

## 📈 Visual Insights

### AIX Node Growth  
![Node Growth Chart](charts/node_growth_chart.png)

### AIX Holder Growth  
![Holder Growth Chart](charts/holder_growth_chart.png)

### Modeled TAO Emissions (USD)  
![TAO Emissions USD](charts/tao_emissions_chart.png)

---

## 🚀 How to Use

1. Clone this repo  
2. Open notebooks in Colab or Jupyter  
3. Run daily tracker cells to fetch node count or holder count  
4. Charts update automatically from saved CSV logs

---

## 🧪 Data Sources

- [TaoStats.io](https://taostats.io) — subnet emissions and metagraph tracking  
- [Etherscan.io](https://etherscan.io) — AIX token transfers and holder data  
- [Bittensor Python SDK](https://docs.bittensor.com) — Live subnet telemetry  
- [Dune Dashboard](https://dune.com/digidom/digidom87-tao-aix) — Modeled emission trends and token value

---

## 📄 License

MIT — open source. Please reference or fork with attribution.

