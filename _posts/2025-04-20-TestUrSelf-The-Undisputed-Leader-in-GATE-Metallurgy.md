<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TestUrSelf - GATE Metallurgy Coaching | AIR-1 Since 2019</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #3498db;
            --secondary: #2c3e50;
            --accent: #e74c3c;
            --light: #f8f9fa;
            --dark: #333;
            --gray: #7f8c8d;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: #f5f7fa;
            overflow-x: hidden;
        }
        
        .gate-blog-container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
        }
        
        /* Animated Header */
        .blog-header {
            text-align: center;
            margin-bottom: 60px;
            padding: 40px 20px;
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            background: linear-gradient(135deg, var(--secondary), var(--primary));
            color: white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            animation: fadeIn 1s ease-out;
        }
        
        .blog-header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            animation: pulse 15s infinite linear;
        }
        
        .blog-header h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            position: relative;
            text-shadow: 0 2px 4px rgba(0,0,0,0.2);
            animation: slideDown 0.8s ease-out;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            position: relative;
            animation: fadeIn 1.5s ease-out;
        }
        
        .typing-animation {
            display: inline-block;
            overflow: hidden;
            white-space: nowrap;
            border-right: 3px solid white;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        .header-decoration {
            position: absolute;
            bottom: -30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 15px;
        }
        
        .circle {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--primary);
            font-weight: bold;
            animation: bounce 2s infinite ease-in-out;
        }
        
        .circle:nth-child(1) { animation-delay: 0.1s; background: #f1c40f; }
        .circle:nth-child(2) { animation-delay: 0.3s; background: #2ecc71; }
        .circle:nth-child(3) { animation-delay: 0.5s; background: #e74c3c; }
        
        /* Highlight Box */
        .highlight-box {
            background-color: var(--light);
            border-left: 4px solid var(--primary);
            padding: 25px;
            margin: 40px 0;
            border-radius: 0 8px 8px 0;
            position: relative;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .highlight-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        
        .highlight-box::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, rgba(52,152,219,0.1) 0%, rgba(255,255,255,0) 100%);
            z-index: 0;
        }
        
        .highlight-box p {
            position: relative;
            z-index: 1;
            font-size: 1.1rem;
        }
        
        /* Timeline Section */
        .achievement-section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            margin: 50px 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
            position: relative;
            overflow: hidden;
        }
        
        .achievement-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 5px;
            height: 100%;
            background: linear-gradient(to bottom, var(--primary), var(--accent));
        }
        
        .achievement-section h2 {
            color: var(--secondary);
            margin-bottom: 30px;
            display: flex;
            align-items: center;
            font-size: 1.8rem;
        }
        
        .achievement-section h2 .icon {
            margin-right: 15px;
            font-size: 1.5rem;
        }
        
        .timeline {
            position: relative;
            padding-left: 80px;
            margin: 40px 0;
        }
        
        .timeline::before {
            content: '';
            position: absolute;
            left: 35px;
            top: 0;
            bottom: 0;
            width: 3px;
            background: var(--primary);
            z-index: 1;
        }
        
        .timeline-item {
            position: relative;
            margin-bottom: 40px;
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.6s ease-out;
        }
        
        .timeline-item.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .year {
            position: absolute;
            left: -80px;
            top: 0;
            width: 70px;
            height: 70px;
            border-radius: 50%;
            background: var(--primary);
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.2rem;
            box-shadow: 0 5px 15px rgba(52,152,219,0.3);
            z-index: 2;
            transition: all 0.3s;
        }
        
        .timeline-item:hover .year {
            transform: scale(1.1);
        }
        
        .timeline-item.current .year {
            background: var(--accent);
            box-shadow: 0 5px 20px rgba(231,76,60,0.4);
            animation: pulse 2s infinite;
        }
        
        .content {
            padding: 25px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            margin-left: 30px;
            border-left: 3px solid var(--primary);
            transition: all 0.3s;
            position: relative;
        }
        
        .timeline-item:hover .content {
            transform: translateX(10px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }
        
        .content::before {
            content: '';
            position: absolute;
            left: -10px;
            top: 25px;
            width: 20px;
            height: 20px;
            background: white;
            transform: rotate(45deg);
            border-left: 1px solid #eee;
            border-bottom: 1px solid #eee;
        }
        
        .footnote {
            font-style: italic;
            text-align: center;
            margin-top: 30px;
            color: var(--gray);
            font-size: 0.9rem;
        }
        
        /* USP Grid */
        .usp-section {
            margin: 60px 0;
        }
        
        .usp-section h2 {
            color: var(--secondary);
            margin-bottom: 40px;
            display: flex;
            align-items: center;
            font-size: 1.8rem;
        }
        
        .usp-section h2 .icon {
            margin-right: 15px;
            font-size: 1.5rem;
        }
        
        .usp-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }
        
        .usp-card {
            padding: 30px;
            border-radius: 10px;
            background: white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: all 0.4s;
            position: relative;
            overflow: hidden;
            border-top: 3px solid var(--primary);
        }
        
        .usp-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(52,152,219,0.05) 0%, rgba(255,255,255,0) 100%);
            z-index: 0;
        }
        
        .usp-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .usp-card h3 {
            color: var(--secondary);
            margin-top: 0;
            padding-bottom: 15px;
            border-bottom: 1px dashed #eee;
            position: relative;
            z-index: 1;
        }
        
        .usp-card p {
            margin-top: 15px;
            position: relative;
            z-index: 1;
            color: var(--dark);
        }
        
        /* Testimonial Section */
        .testimonial-section {
            background: linear-gradient(135deg, var(--secondary), #1a252f);
            padding: 60px 40px;
            border-radius: 10px;
            margin: 60px 0;
            color: white;
            position: relative;
            overflow: hidden;
        }
        
        .testimonial-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.05) 0%, rgba(255,255,255,0) 70%);
            animation: rotate 20s infinite linear;
        }
        
        .testimonial-section h2 {
            position: relative;
            z-index: 1;
            margin-bottom: 40px;
            display: flex;
            align-items: center;
            font-size: 1.8rem;
        }
        
        .testimonial-section h2 .icon {
            margin-right: 15px;
            font-size: 1.5rem;
        }
        
        .testimonial-card {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 10px;
            position: relative;
            margin: 40px 0;
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.3s;
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 10px;
            left: 10px;
            font-size: 80px;
            color: rgba(255,255,255,0.1);
            font-family: serif;
            line-height: 1;
        }
        
        .quote {
            font-size: 1.1rem;
            font-style: italic;
            position: relative;
            z-index: 1;
            line-height: 1.8;
        }
        
        .author {
            text-align: right;
            font-weight: bold;
            margin-top: 20px;
            color: var(--primary);
        }
        
        .testimonial-stats {
            display: flex;
            justify-content: space-around;
            margin: 50px 0 20px;
            flex-wrap: wrap;
            gap: 20px;
            position: relative;
            z-index: 1;
        }
        
        .stat-item {
            text-align: center;
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 10px;
            min-width: 200px;
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255,255,255,0.1);
            transition: all 0.3s;
        }
        
        .stat-item:hover {
            transform: scale(1.05);
            background: rgba(255,255,255,0.15);
        }
        
        .number {
            font-size: 2.5rem;
            font-weight: bold;
            color: white;
            margin-bottom: 5px;
        }
        
        .label {
            color: rgba(255,255,255,0.8);
            font-size: 0.9rem;
        }
        
        /* Community Section */
        .community-section {
            background: white;
            padding: 50px;
            border-radius: 10px;
            margin: 60px 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        }
        
        .community-section h2 {
            color: var(--secondary);
            margin-bottom: 30px;
            display: flex;
            align-items: center;
            font-size: 1.8rem;
        }
        
        .community-section h2 .icon {
            margin-right: 15px;
            font-size: 1.5rem;
        }
        
        .feature-list {
            list-style-type: none;
        }
        
        .feature-list li {
            padding: 20px;
            margin-bottom: 15px;
            background: var(--light);
            border-left: 4px solid var(--primary);
            border-radius: 0 8px 8px 0;
            position: relative;
            transition: all 0.3s;
        }
        
        .feature-list li:hover {
            transform: translateX(10px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .feature-list li::before {
            content: '✓';
            position: absolute;
            left: -15px;
            top: 50%;
            transform: translateY(-50%);
            width: 30px;
            height: 30px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            box-shadow: 0 3px 10px rgba(52,152,219,0.3);
        }
        
        /* CTA Section */
        .cta-section {
            margin: 80px 0;
        }
        
        .cta-box {
            text-align: center;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 60px 40px;
            border-radius: 15px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 15px 40px rgba(52,152,219,0.3);
        }
        
        .cta-box::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            animation: rotate 20s infinite linear;
        }
        
        .cta-box h2 {
            margin-top: 0;
            font-size: 2rem;
            position: relative;
            z-index: 1;
            margin-bottom: 20px;
        }
        
        .cta-box p {
            max-width: 700px;
            margin: 0 auto 30px;
            position: relative;
            z-index: 1;
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .cta-button {
            display: inline-block;
            background: white;
            color: var(--secondary);
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            margin: 20px 0;
            transition: all 0.3s;
            position: relative;
            z-index: 1;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border: 2px solid white;
            font-size: 1.1rem;
        }
        
        .cta-button:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            background: transparent;
            color: white;
        }
        
        .guarantee-badge {
            font-size: 0.9rem;
            opacity: 0.9;
            display: inline-block;
            padding: 8px 20px;
            background: rgba(255,255,255,0.2);
            border-radius: 50px;
            position: relative;
            z-index: 1;
            margin-top: 20px;
        }
        
        .guarantee-badge .icon {
            margin-right: 5px;
        }
        
        /* Floating Elements */
        .floating-element {
            position: absolute;
            background: rgba(52,152,219,0.1);
            border-radius: 50%;
            z-index: -1;
        }
        
        .floating-element:nth-child(1) {
            width: 200px;
            height: 200px;
            top: 10%;
            left: -100px;
            animation: float 15s infinite ease-in-out;
        }
        
        .floating-element:nth-child(2) {
            width: 300px;
            height: 300px;
            bottom: 10%;
            right: -150px;
            animation: float 20s infinite ease-in-out reverse;
        }
        
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes slideDown {
            from { 
                opacity: 0;
                transform: translateY(-30px);
            }
            to { 
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: white }
        }
        
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.05); opacity: 0.8; }
            100% { transform: scale(1); opacity: 1; }
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(5deg); }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .blog-header h1 {
                font-size: 2rem;
            }
            
            .subtitle {
                font-size: 1rem;
            }
            
            .timeline {
                padding-left: 60px;
            }
            
            .year {
                left: -60px;
                width: 50px;
                height: 50px;
                font-size: 1rem;
            }
            
            .usp-grid {
                grid-template-columns: 1fr;
            }
            
            .testimonial-stats {
                flex-direction: column;
                align-items: center;
            }
            
            .community-section, .achievement-section, .cta-box {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="gate-blog-container">
        <!-- Floating background elements -->
        <div class="floating-element"></div>
        <div class="floating-element"></div>
        
        <!-- Animated Header -->
        <header class="blog-header">
            <h1 class="header-text">TestUrSelf: The Undisputed Leader in GATE Metallurgy AIR-1 Production Since 2019</h1>
            <p class="subtitle typing-animation">Discover the proven system behind our unbroken streak of top rankers</p>
            <div class="header-decoration">
                <div class="circle">2019</div>
                <div class="circle">2024</div>
                <div class="circle">AIR-1</div>
            </div>
        </header>

        <!-- Interactive Intro Section -->
        <section class="intro-section">
            <div class="highlight-box pulse-animation">
                <p><strong>Consistent excellence isn't accidental</strong> - it's engineered. Since 2019, TestUrSelf has dominated GATE Metallurgical Engineering coaching, producing <strong>AIR-1 rankers every consecutive year</strong>. This unparalleled achievement reflects our scientific approach to exam preparation, blending conceptual depth with strategic execution.</p>
            </div>
        </section>

        <!-- Achievement Timeline -->
        <section class="achievement-section">
            <h2><span class="icon">🏆</span> The TestUrSelf Legacy: A Timeline of Excellence</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="year">2019</div>
                    <div class="content">First AIR-1 in GATE MT - The legacy begins with our revolutionary teaching methodology</div>
                </div>
                <div class="timeline-item">
                    <div class="year">2020</div>
                    <div class="content">Back-to-back AIR-1 achievement, proving our system's reliability</div>
                </div>
                <div class="timeline-item">
                    <div class="year">2021</div>
                    <div class="content">Expanded our program with advanced test series and personalized mentoring</div>
                </div>
                <div class="timeline-item">
                    <div class="year">2022</div>
                    <div class="content">Introduced AI-powered performance analytics for precise preparation</div>
                </div>
                <div class="timeline-item">
                    <div class="year">2023</div>
                    <div class="content">Record-breaking 12 students in top 10 ranks across GATE MT</div>
                </div>
                <div class="timeline-item current">
                    <div class="year">2024</div>
                    <div class="content">Continuing our tradition of excellence with innovative learning modules</div>
                </div>
            </div>
            <p class="footnote">Our toppers don't just secure ranks - they redefine expectations with comprehensive subject mastery and exceptional problem-solving skills.</p>
        </section>

        <!-- USP Grid -->
        <section class="usp-section">
            <h2><span class="icon">🔑</span> The TestUrSelf Advantage: Why We Deliver Results</h2>
            
            <div class="usp-grid">
                <div class="usp-card">
                    <h3><i class="fas fa-chalkboard-teacher"></i> Elite Faculty Team</h3>
                    <p>Learn from GATE toppers and alumni of ISM, NITs, and IISc who bring both academic excellence and practical exam insights. Our faculty includes 5 former AIR-1 holders.</p>
                </div>
                
                <div class="usp-card">
                    <h3><i class="fas fa-book"></i> Syllabus-First Design</h3>
                    <p>Content meticulously structured based on decade-long GATE trend analysis and weightage patterns. Updated weekly with current question trends.</p>
                </div>
                
                <div class="usp-card">
                    <h3><i class="fas fa-database"></i> Premium Question Bank</h3>
                    <p>2000+ handcrafted problems matching GATE's evolving difficulty level, with detailed solution frameworks and multiple solving approaches.</p>
                </div>
                
                <div class="usp-card">
                    <h3><i class="fas fa-lightbulb"></i> Concept-Centric Approach</h3>
                    <p>We build fundamental understanding first - the key to solving even the most unconventional GATE problems. 80% concept focus, 20% rote learning.</p>
                </div>
                
                <div class="usp-card">
                    <h3><i class="fas fa-user-cog"></i> Personalized Roadmaps</h3>
                    <p>Customized study plans with weekly targets and adaptive adjustments based on performance metrics. AI-driven recommendations for optimal preparation.</p>
                </div>
                
                <div class="usp-card">
                    <h3><i class="fas fa-chart-line"></i> Smart Analytics Dashboard</h3>
                    <p>Real-time rank predictors, strength-weakness matrices, and comparative analysis with topper benchmarks. Track your progress with precision.</p>
                </div>
            </div>
        </section>

        <!-- Testimonial Section -->
        <section class="testimonial-section">
            <h2><span class="icon">💬</span> Voices of Our Champions</h2>
            
            <div class="testimonial-slider">
                <div class="testimonial-card active">
                    <div class="quote">"The TestUrSelf test series was instrumental in my AIR-1 achievement. The questions perfectly simulated GATE's complexity, while the faculty's mentorship helped me develop winning strategies. The detailed solutions booklet was my bible during last month preparation."</div>
                    <div class="author">- GATE MT 2023 Topper (AIR-1)</div>
                </div>
                
                <div class="testimonial-card">
                    <div class="quote">"What sets TestUrSelf apart is their focus on conceptual clarity. Their material doesn't just prepare you for GATE but builds a strong foundation for metallurgical engineering. The regular doubt sessions were incredibly helpful."</div>
                    <div class="author">- GATE MT 2022 Topper (AIR-3)</div>
                </div>
                
                <div class="testimonial-card">
                    <div class="quote">"The personalized attention I received was game-changing. My mentor identified my weak areas early and created a customized plan that helped me jump from 200s rank to AIR-7 in just 4 months."</div>
                    <div class="author">- GATE MT 2021 Topper (AIR-7)</div>
                </div>
            </div>
            
            <div class="testimonial-nav">
                <button class="testimonial-prev"><i class="fas fa-chevron-left"></i></button>
                <div class="testimonial-dots">
                    <span class="dot active"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                </div>
                <button class="testimonial-next"><i class="fas fa-chevron-right"></i></button>
            </div>
            
            <div class="testimonial-stats">
                <div class="stat-item">
                    <div class="number">100%</div>
                    <div class="label">AIR-1 Success Rate Since 2019</div>
                </div>
                <div class="stat-item">
                    <div class="number">47+</div>
                    <div class="label">Top 100 Rankers in 2024</div>
                </div>
                <div class="stat-item">
                    <div class="number">5.0★</div>
                    <div class="label">Average Student Rating</div>
                </div>
            </div>
        </section>

        <!-- Community Section -->
        <section class="community-section">
            <h2><span class="icon">🤝</span> Beyond Ranks: Building a Community of Achievers</h2>
            <ul class="feature-list">
                <li><strong>Comprehensive Support System:</strong> Weekly doubt-clearing sessions, monthly mock interviews, and PSU preparation workshops with retired PSU executives</li>
                <li><strong>Peer Learning Network:</strong> Collaborate with high-achieving peers through dedicated study groups and problem-solving forums</li>
                <li><strong>Alumni Guidance:</strong> Connect with past toppers for mentorship and career advice through our exclusive alumni network</li>
                <li><strong>Post-GATE Roadmap:</strong> Specialized guidance for M.Tech admissions (IISc, IITs), PSU placements, and research opportunities abroad</li>
                <li><strong>Research Opportunities:</strong> Our top performers get direct recommendations for research positions at premier institutes</li>
                <li><strong>Industry Connect:</strong> Regular webinars with industry leaders from Tata Steel, SAIL, and Vedanta Resources</li>
            </ul>
        </section>

        <!-- Interactive Demo Section -->
        <section class="demo-section">
            <h2><span class="icon">🎮</span> Experience Our Learning Platform</h2>
            <div class="demo-container">
                <div class="demo-tabs">
                    <button class="demo-tab active" data-tab="video">Video Lectures</button>
                    <button class="demo-tab" data-tab="test">Test Series</button>
                    <button class="demo-tab" data-tab="analytics">Performance Analytics</button>
                </div>
                <div class="demo-content">
                    <div class="demo-item active" id="video-demo">
                        <div class="demo-video">
                            <div class="video-placeholder">
                                <i class="fas fa-play"></i>
                                <p>Sample Lecture: Phase Transformations in Steel</p>
                            </div>
                        </div>
                        <div class="demo-desc">
                            <h3>Interactive Video Lectures</h3>
                            <p>Our HD lectures with real-time annotations and bookmarking features help you grasp complex concepts easily. Speed control, transcript search, and integrated notes make learning efficient.</p>
                            <button class="demo-cta">View Sample Lecture</button>
                        </div>
                    </div>
                    <div class="demo-item" id="test-demo">
                        <div class="demo-image">
                            <img src="https://via.placeholder.com/500x300" alt="Test Series Demo">
                        </div>
                        <div class="demo-desc">
                            <h3>Comprehensive Test Series</h3>
                            <p>Experience our GATE-simulated tests with detailed solutions and percentile rankings. Our adaptive tests identify your weak areas automatically.</p>
                            <button class="demo-cta">Try Free Test</button>
                        </div>
                    </div>
                    <div class="demo-item" id="analytics-demo">
                        <div class="demo-image">
                            <img src="https://via.placeholder.com/500x300" alt="Analytics Dashboard">
                        </div>
                        <div class="demo-desc">
                            <h3>Smart Analytics Dashboard</h3>
                            <p>Track your preparation with our advanced analytics that compares your performance with previous toppers and suggests improvement areas.</p>
                            <button class="demo-cta">View Sample Report</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA Section -->
        <section class="cta-section">
            <div class="cta-box">
                <h2>Ready to Begin Your AIR-1 Journey?</h2>
                <p>GATE MT is more than an exam - it's a gateway to your future. With TestUrSelf, you're not just preparing; you're engineering success. Join hundreds of successful metallurgists who transformed their careers with our program.</p>
                <a href="https://www.testurself.in" class="cta-button">Join the Toppers' Community Today</a>
                <div class="guarantee-badge">
                    <span class="icon">✓</span> Proven Success System | <span class="icon">👨‍🎓</span> 5+ Years of Excellence | <span class="icon">💰</span> 100% Satisfaction Guarantee
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <div class="footer-content">
                <div class="footer-logo">
                    <h3>TestUrSelf</h3>
                    <p>Engineering Success Since 2019</p>
                </div>
                <div class="footer-links">
                    <div class="footer-col">
                        <h4>Programs</h4>
                        <ul>
                            <li><a href="#">GATE MT Comprehensive</a></li>
                            <li><a href="#">Test Series</a></li>
                            <li><a href="#">Crash Course</a></li>
                            <li><a href="#">PSU Interview Prep</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h4>Resources</h4>
                        <ul>
                            <li><a href="#">Free Materials</a></li>
                            <li><a href="#">Previous Papers</a></li>
                            <li><a href="#">Syllabus Analysis</a></li>
                            <li><a href="#">Blog</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h4>Company</h4>
                        <ul>
                            <li><a href="#">About Us</a></li>
                            <li><a href="#">Success Stories</a></li>
                            <li><a href="#">Faculty</a></li>
                            <li><a href="#">Contact</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>© 2024 TestUrSelf. All Rights Reserved.</p>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-linkedin"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
        </footer>
    </div>

    <script>
        // Animate timeline items on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const timelineItems = document.querySelectorAll('.timeline-item');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.1 });
            
            timelineItems.forEach(item => {
                observer.observe(item);
            });
            
            // Testimonial slider functionality
            const testimonials = document.querySelectorAll('.testimonial-card');
            const dots = document.querySelectorAll('.dot');
            const prevBtn = document.querySelector('.testimonial-prev');
            const nextBtn = document.querySelector('.testimonial-next');
            let currentIndex = 0;
            
            function showTestimonial(index) {
                testimonials.forEach(testimonial => testimonial.classList.remove('active'));
                dots.forEach(dot => dot.classList.remove('active'));
                
                testimonials[index].classList.add('active');
                dots[index].classList.add('active');
                currentIndex = index;
            }
            
            nextBtn.addEventListener('click', () => {
                currentIndex = (currentIndex + 1) % testimonials.length;
                showTestimonial(currentIndex);
            });
            
            prevBtn.addEventListener('click', () => {
                currentIndex = (currentIndex - 1 + testimonials.length) % testimonials.length;
                showTestimonial(currentIndex);
            });
            
            dots.forEach((dot, index) => {
                dot.addEventListener('click', () => {
                    showTestimonial(index);
                });
            });
            
            // Auto-rotate testimonials
            setInterval(() => {
                currentIndex = (currentIndex + 1) % testimonials.length;
                showTestimonial(currentIndex);
            }, 5000);
            
            // Demo tabs functionality
            const demoTabs = document.querySelectorAll('.demo-tab');
            const demoItems = document.querySelectorAll('.demo-item');
            
            demoTabs.forEach(tab => {
                tab.addEventListener('click', () => {
                    const tabName = tab.getAttribute('data-tab');
                    
                    demoTabs.forEach(t => t.classList.remove('active'));
                    demoItems.forEach(item => item.classList.remove('active'));
                    
                    tab.classList.add('active');
                    document.getElementById(`${tabName}-demo`).classList.add('active');
                });
            });
            
            // Floating element animation
            const floatingElements = document.querySelectorAll('.floating-element');
            floatingElements.forEach((el, index) => {
                el.style.animationDelay = `${index * 2}s`;
            });
        });
    </script>
</body>
</html>
