<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>How to Make Your Website Live - Cyber Cafe Guide</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: #333;
            line-height: 1.6;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            padding: 30px;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
        }
        
        .logo img {
            width: 60px;
            margin-right: 15px;
        }
        
        .logo h1 {
            color: #1a2a6c;
            font-size: 32px;
        }
        
        .tagline {
            color: #555;
            font-size: 18px;
            margin-bottom: 10px;
        }
        
        .section-title {
            color: #1a2a6c;
            margin: 25px 0 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid #fdbb2d;
        }
        
        .steps {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .step-card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        }
        
        .step-number {
            background: #1a2a6c;
            color: white;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-bottom: 15px;
        }
        
        .step-card h3 {
            color: #1a2a6c;
            margin-bottom: 10px;
        }
        
        .providers {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin: 20px 0;
        }
        
        .provider-card {
            background: #f0f8ff;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            border: 1px solid #ddd;
        }
        
        .provider-card h3 {
            color: #1a2a6c;
            margin-bottom: 10px;
        }
        
        .price {
            font-weight: bold;
            color: #b21f1f;
            margin: 10px 0;
        }
        
        .note {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 15px;
            margin: 20px 0;
            border-radius: 4px;
        }
        
        .code-block {
            background: #2b2b2b;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            margin: 15px 0;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
        }
        
        .btn {
            display: inline-block;
            background: #1a2a6c;
            color: white;
            padding: 12px 25px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            margin: 10px 5px;
            transition: background 0.3s;
        }
        
        .btn:hover {
            background: #2a3c9e;
        }
        
        .btn i {
            margin-right: 8px;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #ddd;
            color: #555;
        }
        
        @media (max-width: 768px) {
            .steps, .providers {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <img src="https://cdn-icons-png.flaticon.com/512/3049/3049428.png" alt="Cyber Cafe Logo">
                <h1>Website Live Deployment Guide</h1>
            </div>
            <p class="tagline">Step-by-step instructions to make your cyber cafe website live online</p>
        </header>

        <h2 class="section-title">4 Ways to Make Your Website Live</h2>
        
        <div class="steps">
            <div class="step-card">
                <div class="step-number">1</div>
                <h3>Free Hosting Options</h3>
                <p>Use these free platforms to get your website online quickly:</p>
                <ul>
                    <li>GitHub Pages (Free)</li>
                    <li>Netlify (Free)</li>
                    <li>Vercel (Free)</li>
                    <li>000webhost (Free)</li>
                </ul>
                <a href="#free-hosting" class="btn"><i class="fas fa-external-link-alt"></i> Free Options</a>
            </div>
            
            <div class="step-card">
                <div class="step-number">2</div>
                <h3>Paid Hosting Services</h3>
                <p>For more professional and reliable hosting:</p>
                <ul>
                    <li>Hostinger (₹99/month)</li>
                    <li>Bluehost ($2.95/month)</li>
                    <li>Namecheap ($1.58/month)</li>
                    <li>BigRock (₹199/month)</li>
                </ul>
                <a href="#paid-hosting" class="btn"><i class="fas fa-external-link-alt"></i> Paid Options</a>
            </div>
            
            <div class="step-card">
                <div class="step-number">3</div>
                <h3>Using GitHub Pages (Free)</h3>
                <p>Step-by-step process:</p>
                <ol>
                    <li>Create a GitHub account</li>
                    <li>Create a new repository</li>
                    <li>Upload your HTML file</li>
                    <li>Enable GitHub Pages</li>
                    <li>Your site is live!</li>
                </ol>
                <a href="#github" class="btn"><i class="fab fa-github"></i> GitHub Guide</a>
            </div>
            
            <div class="step-card">
                <div class="step-number">4</div>
                <h3>Using Netlify (Free)</h3>
                <p>Easiest method for beginners:</p>
                <ol>
                    <li>Create a Netlify account</li>
                    <li>Drag & drop your HTML file</li>
                    <li>Your site is instantly live</li>
                    <li>Get a free custom domain</li>
                </ol>
                <a href="#netlify" class="btn"><i class="fas fa-cloud-upload-alt"></i> Netlify Guide</a>
            </div>
        </div>

        <section id="free-hosting">
            <h2 class="section-title">Free Hosting Providers</h2>
            <div class="providers">
                <div class="provider-card">
                    <h3>GitHub Pages</h3>
                    <p>Free for public repositories</p>
                    <p class="price">₹0/month</p>
                    <a href="https://pages.github.com/" class="btn">Visit</a>
                </div>
                
                <div class="provider-card">
                    <h3>Netlify</h3>
                    <p>Free plan available</p>
                    <p class="price">₹0/month</p>
                    <a href="https://www.netlify.com/" class="btn">Visit</a>
                </div>
                
                <div class="provider-card">
                    <h3>Vercel</h3>
                    <p>Free for personal use</p>
                    <p class="price">₹0/month</p>
                    <a href="https://vercel.com/" class="btn">Visit</a>
                </div>
            </div>
        </section>

        <section id="paid-hosting">
            <h2 class="section-title">Paid Hosting Providers</h2>
            <div class="providers">
                <div class="provider-card">
                    <h3>Hostinger</h3>
                    <p>Popular in India</p>
                    <p class="price">₹99/month</p>
                    <a href="https://www.hostinger.in/" class="btn">Visit</a>
                </div>
                
                <div class="provider-card">
                    <h3>Bluehost</h3>
                    <p>WordPress recommended</p>
                    <p class="price">$2.95/month</p>
                    <a href="https://www.bluehost.com/" class="btn">Visit</a>
                </div>
                
                <div class="provider-card">
                    <h3>BigRock</h3>
                    <p>Indian provider</p>
                    <p class="price">₹199/month</p>
                    <a href="https://www.bigrock.in/" class="btn">Visit</a>
                </div>
            </div>
        </section>

        <section id="github">
            <h2 class="section-title">Step-by-Step: GitHub Pages</h2>
            <div class="steps">
                <div class="step-card">
                    <div class="step-number">1</div>
                    <h3>Create Account</h3>
                    <p>Go to <a href="https://github.com/">github.com</a> and create a free account.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">2</div>
                    <h3>Create Repository</h3>
                    <p>Click on "+" → "New repository". Name it "username.github.io" (replace username with your GitHub username).</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">3</div>
                    <h3>Upload Files</h3>
                    <p>Click "Add file" → "Upload files". Drag and drop your HTML file and any related files.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">4</div>
                    <h3>Enable GitHub Pages</h3>
                    <p>Go to Settings → Pages → Select "main" branch → Save.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">5</div>
                    <h3>Access Your Site</h3>
                    <p>Your website will be live at "https://username.github.io" within 1-2 minutes.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">6</div>
                    <h3>Custom Domain (Optional)</h3>
                    <p>In Pages settings, you can add a custom domain if you have one.</p>
                </div>
            </div>
        </section>

        <section id="netlify">
            <h2 class="section-title">Step-by-Step: Netlify</h2>
            <div class="steps">
                <div class="step-card">
                    <div class="step-number">1</div>
                    <h3>Create Account</h3>
                    <p>Go to <a href="https://www.netlify.com/">netlify.com</a> and sign up for free.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">2</div>
                    <h3>Drag & Drop</h3>
                    <p>From the dashboard, drag and drop the folder containing your HTML file.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">3</div>
                    <h3>Your Site is Live</h3>
                    <p>Netlify will instantly deploy your site and give you a URL.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">4</div>
                    <h3>Customize Domain</h3>
                    <p>You can change the auto-generated domain name to something more memorable.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">5</div>
                    <h3>Custom Domain (Optional)</h3>
                    <p>Connect your own domain in the Domain settings section.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">6</div>
                    <h3>Continuous Deployment</h3>
                    <p>Connect to GitHub for automatic updates when you make changes.</p>
                </div>
            </div>
        </section>

        <div class="note">
            <h3><i class="fas fa-lightbulb"></i> Important Note</h3>
            <p>For your cyber cafe website with form processing, you'll need additional backend services. Free hosting options work for static sites, but for form processing you may need to use a service like Formspree or invest in a paid hosting plan with PHP support.</p>
        </div>

        <section>
            <h2 class="section-title">Next Steps After Going Live</h2>
            <ul>
                <li>Share your website link on social media</li>
                <li>Add your website to Google My Business listing</li>
                <li>Tell your customers about your online services</li>
                <li>Consider creating Facebook/Instagram pages for your cyber cafe</li>
                <li>Ask satisfied customers to leave reviews online</li>
            </ul>
        </section>

        <footer>
            <p>Cyber Cafe PVC Printing Services © 2023 | Phone: +91 6202819125</p>
            <p>Address: Mujauna Parsa, Saran, Bihar 841219</p>
        </footer>
    </div>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if(targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if(targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 20,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
