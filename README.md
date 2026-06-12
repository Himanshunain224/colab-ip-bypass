# Cloud Browser IP Bypass 🌐

A practical project built to bypass local network IP blocks and website restrictions by running a browser inside Google Colab's network.

## 📝 How it Works
When a local firewall filters packets or blocks an IP address, traditional methods like changing DNS or restarting the router don't always work. 

This project uses Google Colab to build a separate proxy environment. It boots a virtual desktop and a real Google Chrome instance on Google's network, then tunnels the visual screen directly to your laptop using a secure Cloudflare Tunnel. To your local router, the traffic looks completely legitimate.

## 🚀 How to Use It
1. Upload `work.ipynb` to Google Colab.
2. Run **Cell 1** to install the tools (Chrome, Xvfb, Cloudflare).
3. Run **Cell 2** to start the virtual desktop and open Chrome in the background.
4. Run **Cell 3** to get your secret Cloudflare link.
5. Click the link to open Chrome inside your laptop browser and surf freely!
