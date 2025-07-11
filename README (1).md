# 🌐 Intellectual Galaxy: Wikipedia Network Explorer

**Intellectual Galaxy** is an interactive Streamlit dashboard for visualizing the Wikipedia link networks of Latin American intellectuals. This tool allows users to explore how historical figures are connected through mutual references, and gain insights into gender, nationality, and occupation patterns across the region's intellectual landscape.

---

## 🔍 Project Description

This dashboard invites participants to explore and compare networks of intellectual communities by examining **incoming and outgoing Wikipedia connections** that signal mutual recognition.  
By visualizing and contrasting these graphs, users can uncover disparities in how intellectual legacies are constructed, connected, and acknowledged across different cultural and global contexts.

---

## ✨ Features

- 📖 View full Wikipedia graph for a selected intellectual (e.g. *Gabriela Mistral*)
- 🌐 Interactive 2D and 3D network visualizations with node filtering
- 🧠 Highlights incoming (referenced by) and outgoing (refers to) connections
- 🧬 Hover on nodes to view properties like gender, nationality, birthdate, occupation, and prizes
- 📊 Dataset summary charts for gender and occupation distribution
- 🗺️ Global “galaxy view” of all intellectuals in the dataset
- 🧮 Adjacency matrix computation for the selected person's network
- 🧭 Graph filtering menus, selection tools, and force-directed physics (via PyVis)

---

## 🚀 Live Demo

Try it out:  
🔗 [Streamlit App](https://wikinetworkdashboard-9powvg2cgaspgjvecyrzsv.streamlit.app/)

---

## 📁 Dataset

The dataset was created from **Wikidata** and contains metadata for Latin American intellectuals including:

- Name  
- Gender  
- Nationality  
- Birthdate  
- Occupation  
- Prize (e.g. Nobel)

CSV File: `latin_american_intellectuals.csv`

---

## 🖼️ Screenshots

| Galaxy View of All Intellectuals | Focused Graph of Selected Person |
|----------------------------------|-----------------------------------|
| ![Galaxy View](./assets/galaxy_view.png) | ![Individual View](./assets/person_view.png) |

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/wiki_network_dashboard.git
cd wiki_network_dashboard
pip install -r requirements.txt
streamlit run streamlit_app.py
```

### Requirements

```text
streamlit
wikipedia-api
networkx
pandas
numpy
plotly
pyvis
```

---

## 💡 Usage

1. Launch the app using `streamlit run streamlit_app.py`.
2. Explore the global graph or select a person to visualize individual networks.
3. Use the sidebar to filter by gender or occupation.
4. Hover over nodes for more information.
5. Explore the graph’s physics or enable filters with the PyVis panel.

---

## 📘 How It Works

- **Wikipedia API**: Used to retrieve outgoing and incoming article links
- **Wikidata SPARQL**: Used to retrieve metadata like gender, birthdate, etc.
- **NetworkX**: For creating graph structures
- **Plotly**: For 2D/3D interactive graph rendering
- **PyVis**: For filterable, physics-enabled web-based graphs

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍🎓 Author

Developed by **Touseeq Danish**  
📫 Contact: touseeqkhanswl@gmail.com  
🏛️ University: Claude Bernard University Lyon 1  

---

## 🌟 Acknowledgments

- Memgraph Blog – Graph Visualization Inspiration  
- Wikipedia & Wikidata for open data  
- PyVis and Plotly communities for amazing tools