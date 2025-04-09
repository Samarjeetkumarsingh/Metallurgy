<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="TestUrSelf - India's premier GATE 2026 preparation platform with expert guidance, comprehensive study materials, and proven strategies for top ranks">
    <meta name="keywords" content="GATE 2026, GATE preparation, engineering exam, PSU recruitment, IIT admission, online coaching, test series">
    <meta name="author" content="TestUrSelf">
    <title>GATE 2026 Preparation | TestUrSelf - Your Ultimate Success Partner</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --dark-bg: #121212;
            --darker-bg: #0a0a0a;
            --card-bg: #1e1e1e;
            --accent: #6c63ff;
            --accent-light: #857dff;
            --accent-dark: #554ee6;
            --text-primary: #ffffff;
            --text-secondary: #b3b3b3;
            --success: #4caf50;
            --warning: #ff9800;
            --danger: #f44336;
            --border-radius: 12px;
            --box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
            --transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.7;
            color: var(--text-primary);
            background-color: var(--dark-bg);
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background-color: rgba(18, 18, 18, 0.9);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.2rem 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo-icon {
            width: 40px;
            height: 40px;
            background: var(--accent);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: 700;
            font-size: 1.2rem;
        }
        
        .logo-text {
            font-size: 1.5rem;
            font-weight: 700;
            background: linear-gradient(to right, var(--accent), var(--accent-light));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        nav ul li a {
            color: var(--text-secondary);
            text-decoration: none;
            font-weight: 500;
            transition: var(--transition);
            position: relative;
            padding: 0.5rem 0;
        }
        
        nav ul li a:hover {
            color: var(--text-primary);
        }
        
        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent);
            transition: var(--transition);
        }
        
        nav ul li a:hover::after {
            width: 100%;
        }
        
        .nav-cta {
            display: flex;
            gap: 1rem;
            align-items: center;
        }
        
        .btn {
            padding: 0.7rem 1.5rem;
            border-radius: var(--border-radius);
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            text-decoration: none;
            display: inline-block;
        }
        
        .btn-outline {
            border: 2px solid var(--accent);
            color: var(--accent);
            background: transparent;
        }
        
        .btn-outline:hover {
            background: var(--accent);
            color: white;
            transform: translateY(-2px);
        }
        
        .btn-primary {
            background: var(--accent);
            color: white;
            border: 2px solid var(--accent);
        }
        
        .btn-primary:hover {
            background: var(--accent-dark);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(108, 99, 255, 0.3);
        }
        
        .mobile-menu {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('https://images.unsplash.com/photo-1588072432836-e10032774350?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
            padding: 6rem 0;
            text-align: center;
            position: relative;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }
        
        .hero h1 {
            font-size: 3.2rem;
            margin-bottom: 1.5rem;
            line-height: 1.2;
            font-weight: 800;
        }
        
        .hero p {
            font-size: 1.2rem;
            color: var(--text-secondary);
            margin-bottom: 2.5rem;
            line-height: 1.8;
        }
        
        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
        }
        
        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin-top: 4rem;
            flex-wrap: wrap;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--accent);
            margin-bottom: 0.5rem;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        /* Features Section */
        .features {
            padding: 5rem 0;
            background-color: var(--darker-bg);
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 4rem;
        }
        
        .section-header h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            font-weight: 700;
        }
        
        .section-header p {
            color: var(--text-secondary);
            max-width: 700px;
            margin: 0 auto;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .feature-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 2rem;
            transition: var(--transition);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: var(--box-shadow);
            border-color: var(--accent);
        }
        
        .feature-icon {
            width: 60px;
            height: 60px;
            background: rgba(108, 99, 255, 0.1);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
            color: var(--accent);
            font-size: 1.5rem;
        }
        
        .feature-card h3 {
            font-size: 1.3rem;
            margin-bottom: 1rem;
        }
        
        .feature-card p {
            color: var(--text-secondary);
            margin-bottom: 1.5rem;
        }
        
        .feature-link {
            color: var(--accent);
            text-decoration: none;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: var(--transition);
        }
        
        .feature-link:hover {
            color: var(--accent-light);
            gap: 0.8rem;
        }
        
        /* Blog Section */
        .blog {
            padding: 5rem 0;
        }
        
        .blog-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 3rem;
        }
        
        .blog-header h2 {
            font-size: 2.5rem;
        }
        
        .blog-header p {
            color: var(--text-secondary);
            max-width: 500px;
        }
        
        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }
        
        .blog-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            overflow: hidden;
            transition: var(--transition);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .blog-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--box-shadow);
        }
        
        .blog-image {
            height: 200px;
            overflow: hidden;
        }
        
        .blog-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }
        
        .blog-card:hover .blog-image img {
            transform: scale(1.05);
        }
        
        .blog-content {
            padding: 1.5rem;
        }
        
        .blog-meta {
            display: flex;
            gap: 1rem;
            margin-bottom: 1rem;
            font-size: 0.9rem;
            color: var(--text-secondary);
        }
        
        .blog-meta span {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .blog-meta i {
            color: var(--accent);
        }
        
        .blog-card h3 {
            font-size: 1.3rem;
            margin-bottom: 1rem;
            line-height: 1.4;
        }
        
        .blog-card p {
            color: var(--text-secondary);
            margin-bottom: 1.5rem;
            font-size: 0.95rem;
        }
        
        .blog-tags {
            display: flex;
            gap: 0.5rem;
            flex-wrap: wrap;
            margin-bottom: 1.5rem;
        }
        
        .blog-tag {
            background: rgba(108, 99, 255, 0.1);
            color: var(--accent);
            padding: 0.3rem 0.8rem;
            border-radius: 50px;
            font-size: 0.8rem;
            font-weight: 500;
        }
        
        .read-more {
            color: var(--accent);
            text-decoration: none;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: var(--transition);
        }
        
        .read-more:hover {
            color: var(--accent-light);
            gap: 0.8rem;
        }
        
        /* GATE Preparation Section */
        .gate-prep {
            padding: 5rem 0;
            background-color: var(--darker-bg);
        }
        
        .prep-tabs {
            display: flex;
            gap: 1rem;
            margin-bottom: 2rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 1rem;
        }
        
        .tab-btn {
            background: transparent;
            border: none;
            color: var(--text-secondary);
            font-weight: 600;
            padding: 0.7rem 1.5rem;
            border-radius: var(--border-radius);
            cursor: pointer;
            transition: var(--transition);
            position: relative;
        }
        
        .tab-btn.active {
            color: var(--accent);
            background: rgba(108, 99, 255, 0.1);
        }
        
        .tab-btn::after {
            content: '';
            position: absolute;
            bottom: -1px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent);
            transition: var(--transition);
        }
        
        .tab-btn.active::after {
            width: 100%;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .phase-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .phase-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 2rem;
            transition: var(--transition);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .phase-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--box-shadow);
            border-color: var(--accent);
        }
        
        .phase-card h3 {
            font-size: 1.3rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
        
        .phase-card h3 i {
            color: var(--accent);
        }
        
        .phase-card ul {
            list-style: none;
        }
        
        .phase-card li {
            margin-bottom: 0.8rem;
            padding-left: 1.5rem;
            position: relative;
            color: var(--text-secondary);
        }
        
        .phase-card li::before {
            content: '→';
            position: absolute;
            left: 0;
            color: var(--accent);
        }
        
        /* Testimonials */
        .testimonials {
            padding: 5rem 0;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .testimonial-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 2rem;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .testimonial-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }
        
        .testimonial-avatar {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            overflow: hidden;
        }
        
        .testimonial-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .testimonial-info h4 {
            font-size: 1.1rem;
            margin-bottom: 0.3rem;
        }
        
        .testimonial-info p {
            color: var(--text-secondary);
            font-size: 0.9rem;
        }
        
        .testimonial-rating {
            color: var(--warning);
            margin-bottom: 1rem;
        }
        
        .testimonial-content {
            color: var(--text-secondary);
            font-style: italic;
            line-height: 1.8;
        }
        
        /* CTA Section */
        .cta {
            padding: 5rem 0;
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            text-align: center;
        }
        
        .cta h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
        }
        
        .cta p {
            color: rgba(255, 255, 255, 0.8);
            max-width: 700px;
            margin: 0 auto 2.5rem;
        }
        
        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
        }
        
        .btn-light {
            background: white;
            color: var(--accent-dark);
            border: 2px solid white;
        }
        
        .btn-light:hover {
            background: transparent;
            color: white;
            transform: translateY(-2px);
        }
        
        /* Footer */
        footer {
            background-color: var(--darker-bg);
            padding: 5rem 0 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 3rem;
        }
        
        .footer-col h3 {
            font-size: 1.3rem;
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.8rem;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background: var(--accent);
        }
        
        .footer-col p {
            color: var(--text-secondary);
            margin-bottom: 1.5rem;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 0.8rem;
        }
        
        .footer-links a {
            color: var(--text-secondary);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .footer-links a:hover {
            color: var(--accent);
            transform: translateX(5px);
        }
        
        .footer-links a i {
            color: var(--accent);
            font-size: 0.8rem;
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1.5rem;
        }
        
        .social-link {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-secondary);
            transition: var(--transition);
        }
        
        .social-link:hover {
            background: var(--accent);
            color: white;
            transform: translateY(-3px);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            color: var(--text-secondary);
            font-size: 0.9rem;
        }
        
        /* Back to Top */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 50px;
            height: 50px;
            background: var(--accent);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
            z-index: 99;
            box-shadow: 0 5px 20px rgba(108, 99, 255, 0.3);
        }
        
        .back-to-top.active {
            opacity: 1;
            visibility: visible;
        }
        
        .back-to-top:hover {
            background: var(--accent-dark);
            transform: translateY(-3px);
        }
        
        /* Responsive Styles */
        @media (max-width: 1200px) {
            .hero h1 {
                font-size: 2.8rem;
            }
        }
        
        @media (max-width: 992px) {
            .header-container {
                flex-direction: column;
                gap: 1.5rem;
            }
            
            nav ul {
                gap: 1.5rem;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .hero-stats {
                gap: 2rem;
            }
        }
        
        @media (max-width: 768px) {
            nav {
                display: none;
                width: 100%;
            }
            
            nav.active {
                display: block;
                margin-top: 1.5rem;
            }
            
            nav ul {
                flex-direction: column;
                gap: 1rem;
            }
            
            .mobile-menu {
                display: block;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .blog-header {
                flex-direction: column;
                gap: 1rem;
                text-align: center;
            }
            
            .prep-tabs {
                overflow-x: auto;
                padding-bottom: 0.5rem;
                scrollbar-width: none;
            }
            
            .prep-tabs::-webkit-scrollbar {
                display: none;
            }
            
            .tab-btn {
                white-space: nowrap;
            }
            
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
        }
        
        @media (max-width: 576px) {
            .hero {
                padding: 4rem 0;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .section-header h2 {
                font-size: 2rem;
            }
            
            .cta h2 {
                font-size: 2rem;
            }
            
            .footer-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <div class="logo-icon">TU</div>
                <div class="logo-text">TestUrSelf</div>
            </div>
            
            <div class="mobile-menu">
                <i class="fas fa-bars"></i>
            </div>
            
            <nav>
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">Courses</a></li>
                    <li><a href="#">Test Series</a></li>
                    <li><a href="#">Study Materials</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">About</a></li>
                </ul>
            </nav>
            
            <div class="nav-cta">
                <a href="#" class="btn btn-outline">Login</a>
                <a href="#" class="btn btn-primary">Register</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container hero-content">
            <h1>Master GATE 2026 With India's Top Educators</h1>
            <p>Join 50,000+ successful GATE aspirants who cracked the exam with our comprehensive preparation platform featuring live classes, test series, and personalized mentorship.</p>
            
            <div class="hero-buttons">
                <a href="#" class="btn btn-primary">Explore Courses</a>
                <a href="#" class="btn btn-outline">Free Study Materials</a>
            </div>
            
            <div class="hero-stats">
                <div class="stat-item">
                    <div class="stat-number">98%</div>
                    <div class="stat-label">Success Rate</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">150+</div>
                    <div class="stat-label">Toppers</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">10,000+</div>
                    <div class="stat-label">Questions</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">24/7</div>
                    <div class="stat-label">Doubt Support</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <div class="section-header">
                <h2>Why Choose TestUrSelf?</h2>
                <p>We provide the most comprehensive GATE preparation platform with features designed to maximize your score and minimize your effort</p>
            </div>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chalkboard-teacher"></i>
                    </div>
                    <h3>Expert Faculty</h3>
                    <p>Learn from IIT/NIT alumni with 10+ years of GATE teaching experience and proven track records</p>
                    <a href="#" class="feature-link">
                        Meet Our Faculty
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-book-open"></i>
                    </div>
                    <h3>Comprehensive Study Material</h3>
                    <p>Access 5000+ pages of concise notes, formula sheets, and concept maps for all subjects</p>
                    <a href="#" class="feature-link">
                        View Samples
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-tasks"></i>
                    </div>
                    <h3>Smart Test Series</h3>
                    <p>50+ full-length tests with AI-powered analysis to identify and improve weak areas</p>
                    <a href="#" class="feature-link">
                        Try Free Test
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Performance Analytics</h3>
                    <p>Detailed insights into your preparation with comparative analysis and improvement suggestions</p>
                    <a href="#" class="feature-link">
                        See Demo
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Doubt Support</h3>
                    <p>24/7 access to subject experts through live chat, forums, and scheduled doubt sessions</p>
                    <a href="#" class="feature-link">
                        Ask a Question
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>Mobile Learning</h3>
                    <p>Study on the go with our award-winning mobile app featuring offline access and more</p>
                    <a href="#" class="feature-link">
                        Download App
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section class="blog">
        <div class="container">
            <div class="blog-header">
                <h2>Latest From Our Blog</h2>
                <p>Get expert tips, strategies, and updates to boost your GATE preparation</p>
            </div>
            
            <div class="blog-grid">
                <article class="blog-card">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="GATE Study Plan">
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> April 10, 2025</span>
                            <span><i class="far fa-eye"></i> 2.5K Views</span>
                        </div>
                        <h3>6-Month Intensive Study Plan for GATE 2026</h3>
                        <p>Discover how to maximize your score with our scientifically designed study schedule that balances all subjects effectively.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">Study Plan</span>
                            <span class="blog-tag">Strategy</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <article class="blog-card">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1588072432836-e10032774350?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="GATE Books">
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> April 5, 2025</span>
                            <span><i class="far fa-eye"></i> 3.1K Views</span>
                        </div>
                        <h3>Best Books for GATE 2026 Preparation (Subject-wise)</h3>
                        <p>Our expert panel recommends the most effective books for each subject to build strong fundamentals and problem-solving skills.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">Resources</span>
                            <span class="blog-tag">Books</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <article class="blog-card">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="PSU Recruitment">
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> March 28, 2025</span>
                            <span><i class="far fa-eye"></i> 4.7K Views</span>
                        </div>
                        <h3>Complete Guide to PSU Recruitment Through GATE 2026</h3>
                        <p>Everything you need to know about eligibility criteria, selection process, salary packages, and career growth in top PSUs.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">PSU</span>
                            <span class="blog-tag">Career</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- GATE Preparation Section -->
    <section class="gate-prep">
        <div class="container">
            <div class="section-header">
                <h2>GATE 2026 Preparation Roadmap</h2>
                <p>Follow our proven 3-phase strategy used by toppers to systematically cover the syllabus and maximize your score</p>
            </div>
            
            <div class="prep-tabs">
                <button class="tab-btn active" data-tab="initial">Initial Phase</button>
                <button class="tab-btn" data-tab="preparation">Preparation Phase</button>
                <button class="tab-btn" data-tab="revision">Revision Phase</button>
            </div>
            
            <div id="initial" class="tab-content active">
                <p>Build strong foundations by understanding core concepts and creating an effective study plan. This phase is crucial for setting up your preparation structure.</p>
                
                <div class="phase-cards">
                    <div class="phase-card">
                        <h3><i class="fas fa-search"></i> Concept Clarity Check</h3>
                        <ul>
                            <li>Take diagnostic tests to assess current knowledge</li>
                            <li>Identify strong and weak subject areas</li>
                            <li>Analyze previous year papers for patterns</li>
                            <li>Create personalized study plan</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-book"></i> Syllabus Mastery</h3>
                        <ul>
                            <li>Download official GATE 2026 syllabus</li>
                            <li>Mark topics based on weightage</li>
                            <li>Understand technical and non-technical sections</li>
                            <li>Create syllabus checklist for tracking</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-book-open"></i> Resource Collection</h3>
                        <ul>
                            <li>Select standard reference books</li>
                            <li>Gather quality coaching materials</li>
                            <li>Create digital resource library</li>
                            <li>Avoid frequent switching between materials</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div id="preparation" class="tab-content">
                <p>Systematically cover the entire syllabus with conceptual understanding and regular practice. This is the most intensive phase of your preparation.</p>
                
                <div class="phase-cards">
                    <div class="phase-card">
                        <h3><i class="fas fa-tasks"></i> Strategic Planning</h3>
                        <ul>
                            <li>Create weekly study schedules</li>
                            <li>Allocate time for learning and practice</li>
                            <li>Include buffer time for difficult topics</li>
                            <li>Balance study with adequate breaks</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-edit"></i> Effective Note Making</h3>
                        <ul>
                            <li>Develop shorthand for efficient notes</li>
                            <li>Use diagrams and flowcharts</li>
                            <li>Create formula sheets for quick revision</li>
                            <li>Organize notes by topic and difficulty</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-lightbulb"></i> Concept Mastery</h3>
                        <ul>
                            <li>Focus on understanding over memorizing</li>
                            <li>Relate concepts to practical applications</li>
                            <li>Solve varied problems on each concept</li>
                            <li>Create concept maps for complex topics</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div id="revision" class="tab-content">
                <p>Consolidate your learning, identify gaps, and refine exam strategy. This phase transforms knowledge into high scores.</p>
                
                <div class="phase-cards">
                    <div class="phase-card">
                        <h3><i class="fas fa-sync-alt"></i> Intensive Revision</h3>
                        <ul>
                            <li>Revise using concise notes</li>
                            <li>Focus on important formulas</li>
                            <li>Re-attempt solved problems</li>
                            <li>Take full-length mock tests weekly</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-brain"></i> Stress Management</h3>
                        <ul>
                            <li>Maintain regular sleep schedule</li>
                            <li>Practice meditation techniques</li>
                            <li>Stay positive and motivated</li>
                            <li>Believe in your preparation</li>
                        </ul>
                    </div>
                    
                    <div class="phase-card">
                        <h3><i class="fas fa-clipboard-check"></i> Exam Strategy</h3>
                        <ul>
                            <li>Develop smart question selection</li>
                            <li>Plan section-wise time allocation</li>
                            <li>Prepare for different question types</li>
                            <li>Learn when to skip difficult questions</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials">
        <div class="container">
            <div class="section-header">
                <h2>What Our Students Say</h2>
                <p>Success stories from GATE toppers who transformed their careers with TestUrSelf</p>
            </div>
            
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Rahul Sharma">
                        </div>
                        <div class="testimonial-info">
                            <h4>Rahul Sharma</h4>
                            <p>GATE 2025 AIR 47</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="testimonial-content">
                        "TestUrSelf's test series was a game-changer for me. The detailed analysis helped me identify my weak areas and the faculty support was exceptional. I improved my score by 150 marks in the last 3 months!"
                    </p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Priya Patel">
                        </div>
                        <div class="testimonial-info">
                            <h4>Priya Patel</h4>
                            <p>GATE 2025 AIR 12</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="testimonial-content">
                        "The study material is so well-organized that it saved me hundreds of hours. The concept maps and formula sheets were my secret weapons. I couldn't have achieved AIR 12 without TestUrSelf."
                    </p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://randomuser.me/api/portraits/men/67.jpg" alt="Amit Singh">
                        </div>
                        <div class="testimonial-info">
                            <h4>Amit Singh</h4>
                            <p>GATE 2025 AIR 89</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <p class="testimonial-content">
                        "As a working professional, the mobile app was a lifesaver. I could study during commute and the weekend doubt sessions helped clear all my concepts. Got selected in ONGC with AIR 89!"
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta">
        <div class="container">
            <h2>Ready to Start Your GATE 2026 Journey?</h2>
            <p>Join India's most trusted GATE preparation platform and get access to expert guidance, comprehensive study materials, and personalized mentorship.</p>
            
            <div class="cta-buttons">
                <a href="#" class="btn btn-light">Explore Courses</a>
                <a href="#" class="btn btn-outline">Free Demo Class</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>About TestUrSelf</h3>
                    <p>India's premier online learning platform for GATE, ESE, and other engineering competitive exams with a mission to make quality education accessible.</p>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Home</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> About Us</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Courses</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Test Series</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Study Materials</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Exams</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> GATE</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> UPSC ESE</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> BARC OCES</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> ISRO</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> DRDO</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> State Engineering Exams</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Contact Us</h3>
                    <p><i class="fas fa-map-marker-alt"></i> 123 Education Street, Bangalore, India - 560001</p>
                    <p><i class="fas fa-phone-alt"></i> +91 9876543210</p>
                    <p><i class="fas fa-envelope"></i> contact@testurself.com</p>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2025 TestUrSelf. All Rights Reserved. | <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a> | <a href="#">Refund Policy</a></p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <div class="back-to-top">
        <i class="fas fa-arrow-up"></i>
    </div>

    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.querySelector('.mobile-menu');
        const nav = document.querySelector('nav');
        
        mobileMenuBtn.addEventListener('click', () => {
            nav.classList.toggle('active');
        });

        // Tab Functionality
        const tabBtns = document.querySelectorAll('.tab-btn');
        const tabContents = document.querySelectorAll('.tab-content');
        
        tabBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                // Remove active class from all buttons and contents
                tabBtns.forEach(btn => btn.classList.remove('active'));
                tabContents.forEach(content => content.classList.remove('active'));
                
                // Add active class to clicked button and corresponding content
                btn.classList.add('active');
                const tabId = btn.getAttribute('data-tab');
                document.getElementById(tabId).classList.add('active');
            });
        });

        // Back to Top Button
        const backToTopBtn = document.querySelector('.back-to-top');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopBtn.classList.add('active');
            } else {
                backToTopBtn.classList.remove('active');
            }
        });
        
        backToTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Smooth Scrolling for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Animation on Scroll
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.feature-card, .blog-card, .phase-card, .testimonial-card');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.2;
                
                if (elementPosition < screenPosition) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };

        // Set initial state for animated elements
        document.querySelectorAll('.feature-card, .blog-card, .phase-card, .testimonial-card').forEach(element => {
            element.style.opacity = '0';
            element.style.transform = 'translateY(20px)';
            element.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
        });

        // Run animation check on load and scroll
        window.addEventListener('load', animateOnScroll);
        window.addEventListener('scroll', animateOnScroll);
    </script>
</body>
</html>
