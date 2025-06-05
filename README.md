# 🌐 Domain Name Availability Checker

A web application that allows users to check the availability of domain names in real-time. Built with Node.js and Express.js, it integrates with the Domainr API to deliver accurate domain status updates.

---

## 🚀 Features

- **Real-Time Checks** – Instantly verify if a domain name is available
- **User-Friendly Interface** – Simple and intuitive UI
- **API Integration** – Uses [Domainr API](https://domainr.com/docs/api)
- **Responsive Design** – Works well on all screen sizes

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **API**: Domainr API
- **Styling**: Tailwind CSS

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/truelearnerarjun/client.git
   cd client


   Install dependencies
   

🔍 How to Use
Go to the homepage.

Enter a domain (e.g., example.com).

Click Check Availability.

See if it’s available or already registered.

📄 API Details (Domainr)
Endpoint: https://api.domainr.com/v2/status

Method: GET

Required Parameters:

domain – the domain name to check

client_id – your Domainr API client ID

Example Request:

http
Copy
Edit
GET https://api.domainr.com/v2/status?client_id=your_client_id&domain=example.com
Sample Response:

json
Copy
Edit
{
  "status": [
    {
      "domain": "example.com",
      "zone": "com",
      "status": "active",
      "summary": "active"
    }
  ]
}
📁 Project Structure
pgsql
Copy
Edit
client/
├── public/
│   ├── index.html
│   └── styles.css
├── src/
│   ├── app.js
│   └── routes/
│       └── domain.js
├── .env
├── package.json
└── README.md
🤝 Contributing
Feel free to fork this repo and submit pull requests to improve functionality or design
