<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GATE MT Syllabus | TestUrSelf - Producing Top Rankers Since 2018</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #FF6B6B;
            --secondary: #48DBFB;
            --accent: #1DD1A1;
            --gold: #FFD700;
            --text: #F1F2F6;
            --dark-bg: #1A1A2E;
            --darker-bg: #16213E;
            --card-bg: #2D3748;
            --highlight: rgba(255, 215, 0, 0.1);
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.8;
            color: var(--text);
            background-color: var(--darker-bg);
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(29, 209, 161, 0.1) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(255, 107, 107, 0.1) 0%, transparent 20%);
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--dark-bg) 0%, #0F3460 100%);
            padding: 60px 0 40px;
            text-align: center;
            border-bottom: 4px solid var(--accent);
            margin-bottom: 40px;
            box-shadow: 0 15px 30px rgba(0,0,0,0.4);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: "";
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,215,0,0.05) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
        }
        
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        h1 {
            margin: 0;
            font-size: 3rem;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 700;
            text-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }
        
        .subtitle {
            font-size: 1.3rem;
            color: var(--secondary);
            margin-top: 15px;
            font-weight: 500;
        }
        
        .rankers-badge {
            display: inline-block;
            background: linear-gradient(135deg, var(--gold) 0%, #FFA500 100%);
            color: #1A1A2E;
            padding: 8px 20px;
            border-radius: 30px;
            font-weight: 700;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(255, 215, 0, 0.3);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .achievements {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
            flex-wrap: wrap;
        }
        
        .achievement-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 10px;
            padding: 20px;
            min-width: 200px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.2);
            transition: all 0.3s ease;
        }
        
        .achievement-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
            border-color: var(--accent);
        }
        
        .achievement-card i {
            font-size: 2.5rem;
            color: var(--gold);
            margin-bottom: 10px;
        }
        
        .achievement-card h3 {
            color: var(--gold);
            margin: 0;
            font-size: 1.8rem;
        }
        
        .achievement-card p {
            margin-top: 5px;
            font-size: 0.9rem;
            opacity: 0.9;
        }
        
        /* Navigation Styles */
        .syllabus-nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 40px 0;
            position: sticky;
            top: 20px;
            z-index: 100;
        }
        
        .nav-btn {
            padding: 14px 25px;
            background: var(--card-bg);
            border: none;
            color: var(--text);
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 600;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.95rem;
        }
        
        .nav-btn i {
            font-size: 1.1rem;
        }
        
        .nav-btn:hover, .nav-btn.active {
            background: var(--primary);
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255, 107, 107, 0.4);
        }
        
        /* Main Content Styles */
        .section-card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 40px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            border-left: 6px solid var(--accent);
            transition: transform 0.4s ease, box-shadow 0.4s ease;
            display: none;
            position: relative;
            overflow: hidden;
        }
        
        .section-card::before {
            content: "";
            position: absolute;
            top: 0;
            right: 0;
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, rgba(255,255,255,0.05) 0%, transparent 70%);
        }
        
        .section-card.active {
            display: block;
            animation: fadeInUp 0.6s ease;
        }
        
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .section-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
        }
        
        h2 {
            color: var(--primary);
            font-size: 2rem;
            margin-top: 0;
            padding-bottom: 15px;
            border-bottom: 2px solid rgba(255,255,255,0.1);
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        h2 i {
            font-size: 1.8rem;
        }
        
        h3 {
            color: var(--secondary);
            margin: 30px 0 15px;
            font-size: 1.5rem;
            position: relative;
            padding-left: 20px;
        }
        
        h3::before {
            content: "";
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 8px;
            height: 8px;
            background: var(--accent);
            border-radius: 50%;
        }
        
        ul {
            padding-left: 25px;
        }
        
        li {
            margin-bottom: 12px;
            position: relative;
            padding-left: 25px;
            font-size: 1.05rem;
        }
        
        li:before {
            content: "▹";
            color: var(--accent);
            position: absolute;
            left: 0;
            top: 0;
        }
        
        /* Topic Grid Styles */
        .topic-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 25px;
            margin-top: 25px;
        }
        
        .topic-card {
            background: rgba(255,255,255,0.05);
            border-radius: 12px;
            padding: 20px;
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        
        .topic-card::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(to right, var(--accent), var(--secondary));
            transform: scaleX(0);
            transform-origin: left;
            transition: transform 0.4s ease;
        }
        
        .topic-card:hover {
            background: rgba(255,255,255,0.08);
            border-color: var(--accent);
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .topic-card:hover::after {
            transform: scaleX(1);
        }
        
        .topic-card h4 {
            color: var(--accent);
            margin-top: 0;
            font-size: 1.2rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .topic-card h4 i {
            font-size: 1.1rem;
        }
        
        .importance-badge {
            display: inline-block;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            margin-bottom: 15px;
        }
        
        .high-importance {
            background-color: rgba(255, 71, 87, 0.2);
            color: #ff4757;
            border: 1px solid #ff4757;
        }
        
        .medium-importance {
            background-color: rgba(255, 165, 2, 0.2);
            color: #ffa502;
            border: 1px solid #ffa502;
        }
        
        .low-importance {
            background-color: rgba(72, 219, 251, 0.2);
            color: var(--secondary);
            border: 1px solid var(--secondary);
        }
        
        /* TestUrSelf Platform Section */
        .test-yourself-section {
            background: linear-gradient(135deg, var(--dark-bg) 0%, #0F3460 100%);
            border-radius: 15px;
            padding: 40px;
            margin: 60px 0;
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            border: 1px solid rgba(255,255,255,0.1);
            position: relative;
            overflow: hidden;
        }
        
        .test-yourself-section::before {
            content: "";
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(29,209,161,0.05) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
            z-index: 1;
        }
        
        .test-yourself-content {
            position: relative;
            z-index: 2;
        }
        
        .platform-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .platform-title {
            font-size: 2.2rem;
            color: var(--gold);
            font-weight: 700;
            background: linear-gradient(to right, var(--gold), #FFA500);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }
        
        .platform-logo {
            font-size: 2.5rem;
            color: var(--gold);
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 700;
        }
        
        .platform-logo img {
            height: 50px;
        }
        
        .platform-features {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }
        
        .feature-card {
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 25px;
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        
        .feature-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.3);
            border-color: var(--accent);
        }
        
        .feature-card i {
            font-size: 2.5rem;
            color: var(--accent);
            margin-bottom: 20px;
        }
        
        .feature-card h4 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--text);
        }
        
        .feature-card p {
            opacity: 0.9;
            font-size: 1rem;
        }
        
        .cta-button {
            display: inline-block;
            padding: 15px 35px;
            background: linear-gradient(135deg, var(--accent) 0%, #0be881 100%);
            color: #1A1A2E;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            margin-top: 40px;
            transition: all 0.3s ease;
            font-size: 1.1rem;
            border: none;
            cursor: pointer;
            box-shadow: 0 5px 20px rgba(29, 209, 161, 0.3);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(29, 209, 161, 0.5);
        }
        
        .testimonials {
            margin-top: 60px;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .testimonial-card {
            background: rgba(255,255,255,0.05);
            border-radius: 15px;
            padding: 30px;
            border: 1px solid rgba(255,255,255,0.1);
            position: relative;
            transition: all 0.4s ease;
        }
        
        .testimonial-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
            border-color: var(--gold);
        }
        
        .testimonial-card::before {
            content: """;
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 5rem;
            color: rgba(255,255,255,0.05);
            font-family: serif;
            line-height: 1;
        }
        
        .testimonial-content {
            font-style: italic;
            margin-bottom: 20px;
            position: relative;
            z-index: 2;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-bg);
            font-weight: 700;
            font-size: 1.2rem;
        }
        
        .author-info h5 {
            font-size: 1.1rem;
            margin-bottom: 5px;
            color: var(--gold);
        }
        
        .author-info p {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        /* Search Box Styles */
        .search-box {
            margin: 40px 0;
            position: relative;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .search-box input {
            width: 100%;
            padding: 18px 25px;
            border-radius: 50px;
            border: none;
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            color: var(--text);
            font-size: 1.1rem;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            padding-right: 60px;
            border: 1px solid rgba(255,255,255,0.2);
            transition: all 0.3s ease;
        }
        
        .search-box input:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 5px 25px rgba(29, 209, 161, 0.3);
        }
        
        .search-box i {
            position: absolute;
            right: 25px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--secondary);
            font-size: 1.3rem;
        }
        
        /* Footer Styles */
        footer {
            text-align: center;
            padding: 60px 0 40px;
            margin-top: 80px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: rgba(255,255,255,0.6);
            background: linear-gradient(180deg, rgba(22,33,62,0.8) 0%, rgba(26,26,46,1) 100%);
            position: relative;
        }
        
        footer::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://testurself.com/wp-content/uploads/2023/05/pattern-dark.png') center/cover;
            opacity: 0.1;
            z-index: 1;
        }
        
        .footer-content {
            position: relative;
            z-index: 2;
        }
        
        .footer-logo {
            font-size: 2rem;
            font-weight: 700;
            color: var(--text);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .footer-logo i {
            color: var(--accent);
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .social-links a {
            color: var(--text);
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--accent);
            transform: translateY(-3px);
        }
        
        .copyright {
            margin-top: 30px;
            font-size: 0.9rem;
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .subtitle {
                font-size: 1.1rem;
            }
            
            .achievement-card {
                min-width: 160px;
                padding: 15px;
            }
            
            .achievement-card h3 {
                font-size: 1.5rem;
            }
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .platform-title {
                font-size: 1.8rem;
            }
            
            .nav-btn {
                padding: 12px 20px;
                font-size: 0.9rem;
            }
            
            .section-card {
                padding: 25px;
            }
            
            h2 {
                font-size: 1.7rem;
            }
            
            .topic-grid {
                grid-template-columns: 1fr;
            }
            
            .testimonial-grid {
                grid-template-columns: 1fr;
            }
            
            .test-yourself-section {
                padding: 30px;
            }
        }
        
        @media (max-width: 576px) {
            header {
                padding: 40px 0 30px;
            }
            
            .achievements {
                gap: 15px;
            }
            
            .achievement-card {
                min-width: 120px;
                padding: 12px;
            }
            
            .achievement-card h3 {
                font-size: 1.3rem;
            }
            
            .achievement-card p {
                font-size: 0.8rem;
            }
            
            .syllabus-nav {
                gap: 10px;
            }
            
            .nav-btn {
                padding: 10px 15px;
                font-size: 0.8rem;
            }
            
            .search-box input {
                padding: 15px 20px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <h1>GATE Metallurgy (MT) Syllabus</h1>
            <div class="subtitle">Comprehensive Syllabus Breakdown for GATE 2024 Preparation</div>
            <div class="rankers-badge">
                <i class="fas fa-trophy"></i> Producing Top Rankers Since 2018 | AIR-1 Since 2019
            </div>
            
            <div class="achievements">
                <div class="achievement-card">
                    <i class="fas fa-medal"></i>
                    <h3>5+</h3>
                    <p>Years of Excellence</p>
                </div>
                <div class="achievement-card">
                    <i class="fas fa-user-graduate"></i>
                    <h3>50+</h3>
                    <p>Top 100 Rankers</p>
                </div>
                <div class="achievement-card">
                    <i class="fas fa-award"></i>
                    <h3>3</h3>
                    <p>AIR-1 Achievers</p>
                </div>
                <div class="achievement-card">
                    <i class="fas fa-chalkboard-teacher"></i>
                    <h3>10,000+</h3>
                    <p>Students Mentored</p>
                </div>
            </div>
        </div>
    </header>
    
    <div class="container">
        <div class="search-box">
            <input type="text" placeholder="Search topics in GATE MT syllabus...">
            <i class="fas fa-search"></i>
        </div>
        
        <div class="syllabus-nav">
            <button class="nav-btn active" data-section="math">
                <i class="fas fa-square-root-alt"></i> Engineering Math
            </button>
            <button class="nav-btn" data-section="thermo">
                <i class="fas fa-fire"></i> Metallurgical Thermodynamics
            </button>
            <button class="nav-btn" data-section="transport">
                <i class="fas fa-exchange-alt"></i> Transport Phenomena
            </button>
            <button class="nav-btn" data-section="extractive">
                <i class="fas fa-industry"></i> Extractive Metallurgy
            </button>
            <button class="nav-btn" data-section="physical">
                <i class="fas fa-atom"></i> Physical Metallurgy
            </button>
            <button class="nav-btn" data-section="mechanical">
                <i class="fas fa-cogs"></i> Mechanical Metallurgy
            </button>
            <button class="nav-btn" data-section="manufacturing">
                <i class="fas fa-hammer"></i> Manufacturing Processes
            </button>
        </div>
        
        <!-- Engineering Mathematics -->
        <div class="section-card active" id="math">
            <h2><i class="fas fa-square-root-alt"></i> Section 1: Engineering Mathematics</h2>
            <p>Mathematical foundations essential for metallurgical engineering problems. Master these concepts to solve complex metallurgy problems with ease.</p>
            
            <div class="topic-grid">
                <div class="topic-card">
                    <span class="importance-badge high-importance">High Importance</span>
                    <h4><i class="fas fa-vector-square"></i> Linear Algebra</h4>
                    <ul>
                        <li>Matrices and Determinants</li>
                        <li>Systems of linear equations</li>
                        <li>Eigen values and Eigen vectors</li>
                    </ul>
                </div>
                
                <div class="topic-card">
                    <span class="importance-badge high-importance">High Importance</span>
                    <h4><i class="fas fa-chart-line"></i> Calculus</h4>
                    <ul>
                        <li>Limit, Continuity and Differentiability</li>
                        <li>Partial derivatives</li>
                        <li>Maxima and minima</li>
                        <li>Sequences and series</li>
                        <li>Fourier series</li>
                    </ul>
                </div>
                
                <div class="topic-card">
                    <span class="importance-badge medium-importance">Medium Importance</span>
                    <h4><i class="fas fa-arrows-alt"></i> Vector Calculus</h4>
                    <ul>
                        <li>Gradient; Divergence and Curl</li>
                        <li>Line, Surface and volume integrals</li>
                        <li>Stokes, Gauss and Green's theorems</li>
                    </ul>
                </div>
                
                <div class="topic-card">
                    <span class="importance-badge high-importance">High Importance</span>
                    <h4><i class="fas fa-infinity"></i> Differential Equations</h4>
                    <ul>
                        <li>Linear and non-linear first order ODEs</li>
                        <li>Higher order linear ODEs</li>
                        <li>Laplace transforms</li>
                        <li>PDEs - Laplace, heat and wave equations</li>
                    </ul>
                </div>
                
                <div class="topic-card">
                    <span class="importance-badge medium-importance">Medium Importance</span>
                    <h4><i class="fas fa-dice"></i> Probability and Statistics</h4>
                    <ul>
                        <li>Definitions of probability</li>
                        <li>Mean, median, mode and SD</li>
                        <li>Normal and binomial distributions</li>
                        <li>Linear least squares method</li>
                    </ul>
                </div>
                
                <div class="topic-card">
                    <span class="importance-badge medium-importance">Medium Importance</span>
                    <h4><i class="fas fa-calculator"></i> Numerical Methods</h4>
                    <ul>
                        <li>Solutions of linear and non-linear equations</li>
                        <li>Integration by trapezoidal and Simpson's rule</li>
                        <li>Methods for differential equations</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <!-- Metallurgical Thermodynamics -->
        <div class="section-card" id="thermo">
            <h2><i class="fas fa-fire"></i> Section 2: Metallurgical Thermodynamics</h2>
            <p>Thermodynamic principles applied to metallurgical systems and processes. Essential for understanding phase transformations and reaction kinetics.</p>
            
            <h3>Core Concepts</h3>
            <ul>
                <li>Laws of thermodynamics: First and Second law applications</li>
                <li>Enthalpy, Gibbs and Helmholtz free energy</li>
                <li>Maxwell's relations and Chemical potential</li>
                <li>Applications to metallurgical systems and solutions</li>
            </ul>
            
            <h3>Phase Equilibria</h3>
            <ul>
                <li>Gibbs phase rule and phase equilibria</li>
                <li>Binary phase diagrams and lever rule</li>
                <li>Free-energy vs. composition diagrams</li>
            </ul>
            
            <h3>Thermodynamic Applications</h3>
            <ul>
                <li>Equilibrium constant and Activity concepts</li>
                <li>Ellingham and phase stability diagrams</li>
                <li>Thermodynamics of point defects, surfaces and interfaces</li>
                <li>Adsorption and segregation phenomena</li>
            </ul>
            
            <h3>Electrochemistry</h3>
            <ul>
                <li>Single electrode potential</li>
                <li>Electrochemical cells</li>
                <li>Nernst equation</li>
                <li>Potential-pH diagrams</li>
            </ul>
        </div>
        
        <!-- Transport Phenomena and Rate Processes -->
        <div class="section-card" id="transport">
            <h2><i class="fas fa-exchange-alt"></i> Section 3: Transport Phenomena and Rate Processes</h2>
            <p>Fundamentals of momentum, heat and mass transfer in metallurgical systems. Crucial for process optimization and equipment design.</p>
            
            <h3>Momentum Transfer</h3>
            <ul>
                <li>Concept of viscosity and shell balances</li>
                <li>Bernoulli's equation</li>
                <li>Mechanical energy balance equation</li>
                <li>Flow past surfaces and through pipes</li>
            </ul>
            
            <h3>Heat Transfer</h3>
            <ul>
                <li>Conduction: Fourier's Law, 1-D steady state</li>
                <li>Convection: Heat transfer coefficient relations</li>
                <li>Radiation: Black body radiation laws</li>
            </ul>
            
            <h3>Mass Transfer</h3>
            <ul>
                <li>Diffusion and Fick's laws</li>
                <li>Mass transfer coefficients</li>
            </ul>
            
            <h3>Dimensional Analysis</h3>
            <ul>
                <li>Buckingham Pi theorem</li>
                <li>Significance of dimensionless numbers</li>
            </ul>
            
            <h3>Chemical Kinetics</h3>
            <ul>
                <li>Basic laws of chemical kinetics</li>
                <li>First order reactions and rate constant</li>
                <li>Arrhenius relation</li>
                <li>Heterogeneous reactions and oxidation kinetics</li>
            </ul>
            
            <h3>Electrochemical Kinetics</h3>
            <ul>
                <li>Polarization phenomena</li>
            </ul>
        </div>
        
        <!-- Extractive Metallurgy -->
        <div class="section-card" id="extractive">
            <h2><i class="fas fa-industry"></i> Section 4: Mineral Processing and Extractive Metallurgy</h2>
            <p>Processes for mineral beneficiation and metal extraction. The backbone of metallurgical engineering practice.</p>
            
            <h3>Mineral Processing</h3>
            <ul>
                <li>Comminution techniques and Size classification</li>
                <li>Flotation, Gravity separation methods</li>
                <li>Agglomeration: sintering, pelletizing</li>
            </ul>
            
            <h3>Material and Energy Balances</h3>
            <ul>
                <li>Principles in metallurgical processes</li>
            </ul>
            
            <h3>Non-ferrous Metal Extraction</h3>
            <ul>
                <li>Aluminium production processes</li>
                <li>Copper extraction methods</li>
                <li>Titanium extraction techniques</li>
            </ul>
            
            <h3>Iron and Steel Making</h3>
            <ul>
                <li>Blast furnace: Material and heat balance</li>
                <li>Slag properties and basicity</li>
                <li>Metallurgical coke production</li>
                <li>Alternative iron making (COREX, MIDRE)</li>
            </ul>
            
            <h3>Steel Production</h3>
            <ul>
                <li>Primary steel making: BOF, EAF</li>
                <li>Secondary steel making processes</li>
                <li>Stainless steel manufacturing basics</li>
                <li>Continuous Casting principles</li>
            </ul>
        </div>
        
        <!-- Physical Metallurgy -->
        <div class="section-card" id="physical">
            <h2><i class="fas fa-atom"></i> Section 5: Physical Metallurgy</h2>
            <p>Structure-property relationships in metallic materials. Key to developing new alloys and heat treatment processes.</p>
            
            <h3>Fundamentals</h3>
            <ul>
                <li>Chemical Bonding in materials</li>
                <li>Crystal structure of metals and alloys</li>
                <li>X-ray Diffraction principles</li>
                <li>Optical metallography and SEM imaging</li>
            </ul>
            
            <h3>Crystal Imperfections</h3>
            <ul>
                <li>Point, line and surface defects</li>
                <li>Interfaces: coherent, semi-coherent</li>
            </ul>
            
            <h3>Diffusion in Solids</h3>
            <ul>
                <li>Diffusion equation solutions</li>
                <li>Examples: homogenization, carburization</li>
                <li>Kirkendall effect and Uphill diffusion</li>
                <li>Atomic models for diffusion</li>
            </ul>
            
            <h3>Phase Transformations</h3>
            <ul>
                <li>Nucleation and growth Kinetics</li>
                <li>Solidification in various systems</li>
                <li>Cast structures and segregation</li>
                <li>Solid state transformations</li>
            </ul>
            
            <h3>Heat Treatment</h3>
            <ul>
                <li>TTT and CCT diagrams</li>
                <li>Surface hardening treatments</li>
                <li>Recovery, recrystallization</li>
                <li>Heat treatment of alloys</li>
            </ul>
            
            <h3>Material Properties</h3>
            <ul>
                <li>Electronic, magnetic properties</li>
                <li>Basic forms of corrosion</li>
            </ul>
        </div>
        
        <!-- Mechanical Metallurgy -->
        <div class="section-card" id="mechanical">
            <h2><i class="fas fa-cogs"></i> Section 6: Mechanical Metallurgy</h2>
            <p>Mechanical behavior and deformation mechanisms in metals. Essential for material selection and failure analysis.</p>
            
            <h3>Fundamentals</h3>
            <ul>
                <li>Strain and stress tensors</li>
                <li>Mohr's circle representation</li>
                <li>Elasticity and stiffness tensor</li>
                <li>Yield criteria</li>
            </ul>
            
            <h3>Plastic Deformation</h3>
            <ul>
                <li>Deformation by slip and twinning</li>
            </ul>
            
            <h3>Dislocation Theory</h3>
            <ul>
                <li>Types of dislocations</li>
                <li>Dislocation sources and multiplication</li>
                <li>Stress fields around dislocations</li>
                <li>Partial dislocations and reactions</li>
            </ul>
            
            <h3>Strengthening Mechanisms</h3>
            <ul>
                <li>Work hardening</li>
                <li>Grain boundary strengthening</li>
                <li>Solid solution strengthening</li>
                <li>Precipitation strengthening</li>
            </ul>
            
            <h3>Fracture Behavior</h3>
            <ul>
                <li>Griffith theory</li>
                <li>Fracture toughness</li>
                <li>Ductile to brittle transition</li>
            </ul>
            
            <h3>Fatigue and Creep</h3>
            <ul>
                <li>Cyclic stress strain behavior</li>
                <li>Crack growth in fatigue</li>
                <li>High temperature deformation</li>
                <li>Creep and stress rupture</li>
            </ul>
        </div>
        
        <!-- Manufacturing Processes -->
        <div class="section-card" id="manufacturing">
            <h2><i class="fas fa-hammer"></i> Section 7: Manufacturing Processes</h2>
            <p>Metal processing techniques and quality control methods. Practical knowledge for metallurgical engineers.</p>
            
            <h3>Metal Casting</h3>
            <ul>
                <li>Mould design principles</li>
                <li>Casting practices</li>
                <li>Casting defects</li>
            </ul>
            
            <h3>Metal Forming</h3>
            <ul>
                <li>Hot, warm and cold working</li>
                <li>Rolling, forging, extrusion processes</li>
                <li>Wire drawing and sheet metal forming</li>
                <li>Defects in forming</li>
            </ul>
            
            <h3>Metal Joining</h3>
            <ul>
                <li>Soldering, brazing and welding</li>
                <li>Welding metallurgy</li>
                <li>Defects in welded joints</li>
            </ul>
            
            <h3>Powder Metallurgy</h3>
            <ul>
                <li>Powder production methods</li>
                <li>Compaction and sintering</li>
            </ul>
            
            <h3>Non-destructive Testing</h3>
            <ul>
                <li>Dye-penetrant testing</li>
                <li>Ultrasonic testing</li>
                <li>Radiography and eddy current</li>
                <li>Acoustic emission methods</li>
            </ul>
        </div>
        
        <!-- TestUrSelf Platform Section -->
        <div class="test-yourself-section">
            <div class="test-yourself-content">
                <div class="platform-header">
                    <div>
                        <div class="platform-logo">
                            <i class="fas fa-graduation-cap"></i>
                            <span>TestUrSelf</span>
                        </div>
                        <h2 class="platform-title">The Premier GATE MT Preparation Platform</h2>
                    </div>
                    <img src="https://testurself.com/wp-content/uploads/2023/05/rankers-badge.png" alt="Top Rankers Badge" width="120">
                </div>
                
                <p>Since 2018, TestUrSelf has been the trusted platform for GATE Metallurgy aspirants, producing consistent top rankers including AIR-1 in 2019, 2021, and 2022. Our proven methodology combines comprehensive syllabus coverage with cutting-edge assessment tools.</p>
                
                <div class="platform-features">
                    <div class="feature-card">
                        <i class="fas fa-trophy"></i>
                        <h4>Ranker's Blueprint</h4>
                        <p>Access the exact study plan followed by our AIR-1 and top 10 rankers, including their daily schedules and strategy.</p>
                    </div>
                    
                    <div class="feature-card">
                        <i class="fas fa-brain"></i>
                        <h4>Smart Assessments</h4>
                        <p>AI-powered tests that adapt to your skill level, focusing on weak areas with precision similar to actual GATE patterns.</p>
                    </div>
                    
                    <div class="feature-card">
                        <i class="fas fa-chart-bar"></i>
                        <h4>Performance Analytics</h4>
                        <p>Detailed insights with All India Rank comparison, time management analysis, and topic-wise strength evaluation.</p>
                    </div>
                    
                    <div class="feature-card">
                        <i class="fas fa-book-open"></i>
                        <h4>Dynamic Question Bank</h4>
                        <p>10,000+ MT-specific questions with detailed solutions, including previous year papers and predictive questions.</p>
                    </div>
                    
                    <div class="feature-card">
                        <i class="fas fa-video"></i>
                        <h4>Concept Mastery Series</h4>
                        <p>200+ hours of video lectures by IIT/NIT professors focusing on high-weightage topics and problem-solving techniques.</p>
                    </div>
                    
                    <div class="feature-card">
                        <i class="fas fa-users"></i>
                        <h4>Mentorship Program</h4>
                        <p>Direct access to previous year toppers for personalized guidance and doubt resolution sessions.</p>
                    </div>
                </div>
                
                <button class="cta-button">
                    <i class="fas fa-rocket"></i> Start Your Journey to AIR-1
                </button>
                
                <div class="testimonials">
                    <h3><i class="fas fa-quote-left"></i> Success Stories</h3>
                    
                    <div class="testimonial-grid">
                        <div class="testimonial-card">
                            <div class="testimonial-content">
                                "TestUrSelf's targeted approach helped me identify my weak areas early. The mock tests mirrored the actual GATE difficulty, and the detailed solutions were invaluable. I couldn't have achieved AIR-1 without their guidance."
                            </div>
                            <div class="testimonial-author">
                                <div class="author-avatar">RK</div>
                                <div class="author-info">
                                    <h5>Rahul Kumar</h5>
                                    <p>GATE 2019 AIR-1 | MT</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="testimonial-card">
                            <div class="testimonial-content">
                                "The TestUrSelf platform's analytics helped me optimize my preparation strategy. Their question bank covers every possible variation, and the mentor support was available 24/7 during my preparation."
                            </div>
                            <div class="testimonial-author">
                                <div class="author-avatar">PS</div>
                                <div class="author-info">
                                    <h5>Priya Sharma</h5>
                                    <p>GATE 2021 AIR-3 | MT</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="testimonial-card">
                            <div class="testimonial-content">
                                "As a working professional, TestUrSelf's flexible learning modules and weekend intensive programs helped me balance job and preparation. Their time management techniques were game-changing."
                            </div>
                            <div class="testimonial-author">
                                <div class="author-avatar">AM</div>
                                <div class="author-info">
                                    <h5>Amit Mishra</h5>
                                    <p>GATE 2022 AIR-7 | MT</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <div class="container footer-content">
            <div class="footer-logo">
                <i class="fas fa-graduation-cap"></i>
                <span>TestUrSelf</span>
            </div>
            <p>Transforming GATE Aspirants into Top Rankers Since 2018</p>
            
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
                <a href="#"><i class="fab fa-telegram"></i></a>
            </div>
            
            <div class="copyright">
                &copy; 2024 TestUrSelf Education Pvt. Ltd. All Rights Reserved.<br>
                The Premier GATE Metallurgy Preparation Platform
            </div>
        </div>
    </footer>
    
    <script>
        // Tab navigation functionality
        const navBtns = document.querySelectorAll('.nav-btn');
        const sectionCards = document.querySelectorAll('.section-card');
        
        navBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                // Remove active class from all buttons and cards
                navBtns.forEach(btn => btn.classList.remove('active'));
                sectionCards.forEach(card => card.classList.remove('active'));
                
                // Add active class to clicked button
                btn.classList.add('active');
                
                // Show corresponding section
                const sectionId = btn.getAttribute('data-section');
                document.getElementById(sectionId).classList.add('active');
                
                // Smooth scroll to section
                document.getElementById(sectionId).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Search functionality
        const searchInput = document.querySelector('.search-box input');
        searchInput.addEventListener('input', () => {
            const searchTerm = searchInput.value.toLowerCase().trim();
            
            if (searchTerm === '') {
                sectionCards.forEach(card => card.style.display = 'none');
                navBtns.forEach(btn => {
                    if (btn.classList.contains('active')) {
                        const activeSection = btn.getAttribute('data-section');
                        document.getElementById(activeSection).style.display = 'block';
                    }
                });
                return;
            }
            
            sectionCards.forEach(card => {
                const cardContent = card.textContent.toLowerCase();
                if (cardContent.includes(searchTerm)) {
                    card.style.display = 'block';
                    card.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
                } else {
                    card.style.display = 'none';
                }
            });
        });
        
        // Animation on scroll
        const observerOptions = {
            threshold: 0.1
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate');
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.section-card, .feature-card, .testimonial-card').forEach(card => {
            observer.observe(card);
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
