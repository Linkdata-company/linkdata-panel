<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinkData Panel - Lightweight Control Panel</title>
    <style>
        :root {
            --primary: #2c6bed;
            --primary-dark: #1a56d0;
            --secondary: #f8f9fa;
            --text: #333;
            --light-text: #666;
            --border: #eaeaea;
            --success: #10b981;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }
        
        body {
            background-color: #fdfdfd;
            color: var(--text);
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            overflow: hidden;
            margin-bottom: 30px;
        }
        
        .header {
            text-align: center;
            padding: 40px 20px 30px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            position: relative;
        }
        
        .logo-container {
            margin-bottom: 15px;
        }
        
        .logo {
            height: 50px;
            width: auto;
            filter: brightness(0) invert(1);
        }
        
        h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        h1 a {
            color: inherit;
            text-decoration: none;
        }
        
        .tagline {
            font-size: 1.3rem;
            font-weight: 300;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        
        .nav-links {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 20px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            padding: 8px 16px;
            border-radius: 6px;
            transition: all 0.3s ease;
        }
        
        .nav-links a:hover {
            background: rgba(255, 255, 255, 0.15);
        }
        
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }
        
        .badge {
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 0.85rem;
            font-weight: 600;
            background: rgba(255, 255, 255, 0.2);
        }
        
        .screenshot {
            width: 100%;
            border-bottom: 1px solid var(--border);
        }
        
        .screenshot img {
            width: 100%;
            display: block;
        }
        
        .content {
            padding: 30px;
        }
        
        h2 {
            color: var(--primary);
            margin: 25px 0 15px;
            padding-bottom: 8px;
            border-bottom: 1px solid var(--border);
            font-size: 1.8rem;
        }
        
        h3 {
            margin: 20px 0 10px;
            color: var(--primary-dark);
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature-card {
            background: var(--secondary);
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid var(--primary);
        }
        
        .platforms {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .platform {
            background: #f0f7ff;
            padding: 10px 15px;
            border-radius: 6px;
            font-weight: 500;
            color: var(--primary-dark);
        }
        
        .note {
            background: #fff9e6;
            padding: 15px;
            border-radius: 6px;
            border-left: 4px solid #ffc107;
            margin: 20px 0;
        }
        
        .code-block {
            background: #2d3748;
            color: #e2e8f0;
            padding: 15px;
            border-radius: 6px;
            margin: 15px 0;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
            font-size: 0.95rem;
        }
        
        .code-block code {
            color: #81e6d9;
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            color: var(--light-text);
            font-size: 0.9rem;
            border-top: 1px solid var(--border);
            margin-top: 30px;
        }
        
        @media (max-width: 768px) {
            .feature-grid {
                grid-template-columns: 1fr;
            }
            
            .nav-links {
                flex-direction: column;
                align-items: center;
                gap: 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo-container">
                <img src="https://www.linkdata.com/images/logo.webp" alt="LinkData Logo" class="logo">
            </div>
            <h1><a href="https://www.linkdata.com/">LinkData Panel</a></h1>
            <p class="tagline">Lightweight and powerful control panel for the modern web</p>
            
            <div class="nav-links">
                <a href="https://www.linkdata.com/">LinkData.com</a>
                <a href="https://blog.linkdata.com/">Blogs</a>
                <a href="https://forum.linkdata.com/">Forum</a>
            </div>
            
            <div class="badges">
                <div class="badge">Lint Status</div>
                <div class="badge">Community Support</div>
            </div>
        </div>
        
        <div class="screenshot">
            <img src="https://www.linkdata.com/images/logo.webp" alt="LinkData Panel Web Interface">
        </div>
        
        <div class="content">
            <h2>Welcome!</h2>
            <p><strong>LinkData Panel</strong> is designed to provide administrators with an easy-to-use web and command line interface, enabling them to quickly deploy and manage web domains, mail accounts, DNS zones, and databases from one central dashboard — without the hassle of manually deploying and configuring individual components or services.</p>
            
            <h2>⚡ Features and Services</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <h3>Web Servers</h3>
                    <p>Apache2 and NGINX with PHP-FPM</p>
                </div>
                <div class="feature-card">
                    <h3>PHP Support</h3>
                    <p>Multiple PHP versions (5.6 → 8.4, 8.3 default)</p>
                </div>
                <div class="feature-card">
                    <h3>DNS Management</h3>
                    <p>DNS Server (Bind) with clustering capabilities</p>
                </div>
                <div class="feature-card">
                    <h3>Mail Services</h3>
                    <p>POP/IMAP/SMTP with Anti-Virus, Anti-Spam, and Webmail (ClamAV, SpamAssassin, Sieve, Roundcube)</p>
                </div>
                <div class="feature-card">
                    <h3>Database Support</h3>
                    <p>MariaDB/MySQL and/or PostgreSQL databases</p>
                </div>
                <div class="feature-card">
                    <h3>SSL Certificates</h3>
                    <p>Let's Encrypt SSL support with wildcard certificates</p>
                </div>
                <div class="feature-card">
                    <h3>Security</h3>
                    <p>Firewall with brute-force detection and IP lists (iptables, fail2ban, ipset)</p>
                </div>
            </div>
            
            <h2>🖥️ Supported Platforms and Operating Systems</h2>
            <div class="platforms">
                <div class="platform">Debian 12</div>
                <div class="platform">Debian 11</div>
                <div class="platform">Ubuntu 24.04 LTS</div>
                <div class="platform">Ubuntu 22.04 LTS</div>
                <div class="platform">Ubuntu 20.04 LTS</div>
            </div>
            
            <div class="note">
                <strong>NOTES:</strong><br>
                - LinkData Panel does <strong>not</strong> support 32-bit operating systems.<br>
                - Running on OpenVZ 7 or lower may cause DNS/firewall issues. For VPS we recommend <strong>KVM</strong> or <strong>LXC</strong>.
            </div>
            
            <h2>🚀 Installing LinkData Panel</h2>
            <div class="note">
                <strong>NOTE:</strong> Must be installed on a fresh OS for best results.
            </div>
            
            <h3>Step 1: Log in</h3>
            <div class="code-block">
                <code>ssh root@your.server</code>
            </div>
        </div>
        
        <div class="footer">
            <p>© 2025 LinkData Panel. All rights reserved.</p>
        </div>
    </div>
</body>
</html>
