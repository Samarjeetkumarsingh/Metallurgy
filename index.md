<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samarjeet Kumar Singh | Founder of TestUrSelf</title>
    <meta name="description" content="Education Entrepreneur | GATE Mentor | Transforming Engineering Education">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #FFD700;
            --gold-light: #FFECB3;
            --gold-dark: #C9A227;
            --black: #000000;
            --dark-bg: #121212;
            --darker-bg: #0A0A0A;
            --text: #FFFFFF;
            --text-light: #E0E0E0;
            --accent: #6C63FF;
            --success: #42B883;
            --border-radius: 16px;
            --box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            --transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            --section-padding: 120px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--black);
            color: var(--white);
            line-height: 1.7;
            overflow-x: hidden; 
            max-width:100%;
            width:96%;
        }
         .post-headline{
            display:none
        }
          .post-description{
            display:none
        }

        h1, h2, h3, h4 {
            font-family: 'Playfair Display', serif;
            font-weight: 700;
        }
          .btn-outline {
            border: 2px solid var(--gold);
            color: var(--gold);
            background: transparent;
        }
       

        .btn-outline:hover {
            background: var(--gold);
            color: var(--black);
            transform: translateY(-3px);
            box-shadow: 0 5px 20px rgba(255, 215, 0, 0.3);
        }
         .btn-outline-black {
    border: 2px solid #000000;
    color: #000000;
    background: transparent;
}
 .btn-outline-black:hover {
            background: #000000;
            color:  var(--gold);
            transform: translateY(-3px);
            box-shadow: 0 5px 20px rgba(255, 215, 0, 0.3);
        }
          .btn-primary{
            background: linear-gradient(to right, var(--gold), var(--gold-dark));
            color: var(--black);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(255, 215, 0, 0.4);
        }

       
        /* **Hero Section (Floating Profile Image) ** */
        .hero {
            padding: 6rem 0;
            position: relative;
            overflow: hidden;
            background: radial-gradient(circle at 20% 50%, rgba(255, 215, 0, 0.1) 0%, rgba(0, 0, 0, 0) 50%);
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -10%;
            width: 120%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 215, 0, 0.1) 0%, rgba(0, 0, 0, 0) 70%);
            z-index: -1;
        }

        .hero-content {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            align-items: center;
            gap: 4rem;
        }

        .hero-text {
            flex: 1;
        }

        .hero-image {
            flex: 1;
            position: relative;
            perspective: 1000px;
        }

        .hero-image img {
            width: 100%;
            max-width: 400px;
            border-radius: var(--border-radius);
            border: 5px solid var(--gold);
            box-shadow: var(--box-shadow);
            transform: rotateY(10deg);
            transition: var(--transition);
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0) rotateY(10deg); }
            50% { transform: translateY(-20px) rotateY(10deg); }
            100% { transform: translateY(0) rotateY(10deg); }
        }

        .hero-image::after {
            content: '';
            position: absolute;
            top: -20px;
            left: -20px;
            width: 100%;
            height: 100%;
            border: 2px solid var(--gold);
            border-radius: var(--border-radius);
            z-index: -1;
            transition: var(--transition);
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(to right, var(--gold), var(--gold-light));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            position: relative;
            display: inline-block;
        }

        .hero h1 .name-part {
            display: inline-block;
            transition: all 0.3s ease;
        }

        .hero h1:hover .name-part {
            transform: translateY(-5px) rotate(2deg);
            text-shadow: 0 5px 15px rgba(255, 215, 0, 0.4);
        }

        .hero h1:hover .name-part:nth-child(2) {
            transform: translateY(-7px) rotate(-3deg);
        }

        .hero h1:hover .name-part:nth-child(3) {
            transform: translateY(-3px) rotate(5deg);
        }

        .hero h2 {
            font-size: 1.8rem;
            color: var(--text-light);
            margin-bottom: 2rem;
            font-weight: 400;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--text-light);
            margin-bottom: 3rem;
            max-width: 600px;
        }

        .hero-buttons {
            display: flex;
            gap: 1.5rem;
        }

        .social-links {
            display: flex;
            gap: 1.5rem;
            margin-top: 3rem;
        }

        .social-link {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--gold);
            font-size: 1.3rem;
            transition: var(--transition);
        }

        .social-link:hover {
            background: var(--gold);
            color: var(--black);
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(255, 215, 0, 0.3);
        }

        /* **My Journey Section (Timeline + Stats) ** */
        .journey {
            padding: 6rem 0;
            background: var(--darker-bg);
            position: relative;
            overflow: hidden;
        }

        .journey::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
            opacity: 0.03;
            z-index: 0;
        }

        .section-header {
            text-align: center;
            margin-bottom: 4rem;
            width:100%
        }

        .section-header h2 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            position: relative;
            display: inline-block;
            color:gold;
        }

        .section-header h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--gold);
            border-radius: 2px;
        }

        .section-header p {
            color: var(--text-light);
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.1rem;
        }
        .article-btn{
        position:absolute;
        right:0;
        }

        .timeline {
            position: relative;
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem 0;
        }

        .timeline::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 2px;
            height: 100%;
            background: var(--gold);
        }

        .timeline-item {
            display: flex;
            justify-content: flex-end;
            margin-bottom: 4rem;
            position: relative;
        }

        .timeline-item:nth-child(even) {
            justify-content: flex-start;
        }

        .timeline-content {
            width: 45%;
            padding: 2rem;
            background: rgba(255, 215, 0, 0.05);
            border-radius: var(--border-radius);
            border: 1px solid rgba(255, 215, 0, 0.1);
            transition: var(--transition);
            position: relative;
        }

        .timeline-content:hover {
            transform: translateY(-5px);
            background: rgba(255, 215, 0, 0.1);
            border-color: var(--gold);
            box-shadow: var(--box-shadow);
        }

        .timeline-content::before {
            content: '';
            position: absolute;
            top: 20px;
            right: -10px;
            width: 20px;
            height: 20px;
            background: var(--gold);
            border-radius: 50%;
            z-index: 1;
        }

        .timeline-item:nth-child(even) .timeline-content::before {
            right: auto;
            left: -10px;
        }

        .timeline-year {
            font-size: 1.2rem;
            font-weight: 700;
            color: var(--gold);
            margin-bottom: 0.5rem;
        }

        .timeline-title {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: gold;
        }

        .timeline-desc {
            color: var(--text-light);
        }

        .journey-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 4rem;
        }

        .stat-card {
            background: rgba(255, 215, 0, 0.05);
            border: 1px solid rgba(255, 215, 0, 0.1);
            border-radius: var(--border-radius);
            padding: 2rem;
            text-align: center;
            transition: var(--transition);
        }

        .stat-card:hover {
            transform: translateY(-5px);
            background: rgba(255, 215, 0, 0.1);
            border-color: var(--gold);
            box-shadow: var(--box-shadow);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            background: linear-gradient(to right, var(--gold), var(--gold-light));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            font-size: 1rem;
            color: var(--text-light);
        }

        /* **Enhanced Blog Section with Tabs ** */
        .blog {
            padding: 6rem 0;
            background: var(--black);
            position: relative;
        }

        .blog::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
            opacity: 0.03;
            z-index: 0;
        }

        .blog-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            margin-bottom: 3rem;
        }

        .blog-header h2 {
            font-size: 2.8rem;
        }

        .blog-header p {
            color: var(--text-light);
            max-width: 500px;
            text-align: center;
        }

        /* Blog Tabs */
        .blog-tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 3rem;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .blog-tab {
            padding: 0.8rem 1.8rem;
            border-radius: 50px;
            background: transparent;
            color: var(--text-light);
            border: 2px solid rgba(255, 215, 0, 0.3);
            cursor: pointer;
            font-weight: 600;
            transition: var(--transition);
            position: relative;
            overflow: hidden;
            z-index: 1;
        }

        .blog-tab::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 0;
            height: 100%;
            background: linear-gradient(to right, var(--gold), var(--gold-dark));
            transition: var(--transition);
            z-index: -1;
        }

        .blog-tab:hover {
            color: var(--black);
        }

        .blog-tab:hover::before {
            width: 100%;
        }

        .blog-tab.active {
            background: linear-gradient(to right, var(--gold), var(--gold-dark));
            color: var(--black);
            border-color: var(--gold);
            box-shadow: 0 5px 15px rgba(255, 215, 0, 0.3);
        }

        /* Blog Grid */
        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2.5rem;
        }

        .blog-card {
            background: var(--darker-bg);
            border-radius: var(--border-radius);
            overflow: hidden;
            transition: var(--transition);
            border: 1px solid rgba(255, 215, 0, 0.1);
            position: relative;
        }

        .blog-card:hover {
            transform: translateY(-10px);
            box-shadow: var(--box-shadow);
            border-color: var(--gold);
        }

        .blog-image {
            height: 250px;
            overflow: hidden;
            position: relative;
        }

        .blog-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .blog-card:hover .blog-image img {
            transform: scale(1.1);
        }

        .blog-category {
            position: absolute;
            top: 15px;
            right: 15px;
            background: rgba(0, 0, 0, 0.8);
            color: var(--gold);
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-size: 0.8rem;
            font-weight: 600;
            z-index: 2;
        }

        .blog-content {
            padding: 2rem;
        }

        .blog-meta {
            display: flex;
            gap: 1.5rem;
            margin-bottom: 1rem;
            font-size: 0.9rem;
            color: var(--text-light);
        }

        .blog-meta span {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .blog-meta i {
            color: var(--gold);
        }

        .blog-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            line-height: 1.4;
            color: gold;
        }

        .blog-card p {
            color: var(--text-light);
            margin-bottom: 1.5rem;
        }

        .blog-tags {
            display: flex;
            gap: 0.8rem;
            flex-wrap: wrap;
            margin-bottom: 1.5rem;
        }

        .blog-tag {
            background: rgba(255, 215, 0, 0.1);
            color: var(--gold);
            padding: 0.4rem 1rem;
            border-radius: 50px;
            font-size: 0.85rem;
            font-weight: 500;
            transition: var(--transition);
        }

        .blog-tag:hover {
            background: var(--gold);
            color: var(--black);
        }

        .read-more {
            color: var(--gold);
            text-decoration: none;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: var(--transition);
        }

        .read-more:hover {
            gap: 0.8rem;
        }

        /* **Featured Post (Highlighted) ** */
        .featured-post {
            grid-column: span 2;
        }

        .featured-post .blog-image {
            height: 350px;
        }

        .featured-post h3 {
            font-size: 2rem;
            color: gold;
        }

        /* **Testimonials (Interactive Cards) ** */
        .testimonials {
            padding: 6rem 0;
            background: var(--darker-bg);
            position: relative;
        }

        .testimonials::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1523240795612-9a054b0db644?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
            opacity: 0.03;
            z-index: 0;
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2.5rem;
        }

        .testimonial-card {
            background: var(--black);
            border-radius: var(--border-radius);
            padding: 2.5rem;
            border: 1px solid rgba(255, 215, 0, 0.1);
            transition: var(--transition);
        }

        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--box-shadow);
            border-color: var(--gold);
        }

        .testimonial-header {
            display: flex;
            align-items: center;
            gap: 1.5rem;
            margin-bottom: 1.5rem;
        }

        .testimonial-avatar {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid var(--gold);
        }

        .testimonial-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .testimonial-info h4 {
        color: white;
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
        }

        .testimonial-info p {
            color: var(--text-light);
            font-size: 0.95rem;
        }

        .testimonial-rating {
            color: var(--gold);
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }

        .testimonial-text {
            color: var(--text-light);
            font-style: italic;
            line-height: 1.8;
            position: relative;
            padding-left: 1.5rem;
        }

        .testimonial-text::before {
            content: '"';
            position: absolute;
            left: 0;
            top: -10px;
            font-size: 3rem;
            color: var(--gold);
            opacity: 0.3;
            font-family: serif;
        }

        /* **CTA Section (Gold Gradient) ** */
        .cta {
            padding: 6rem 0;
            background: linear-gradient(135deg, var(--gold), var(--gold-dark));
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .cta::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            z-index: 0;
        }

        .cta-content {
            position: relative;
            z-index: 1;
        }

        .cta h2 {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            color: var(--black);
        }

        .cta p {
            color: rgba(0, 0, 0, 0.8);
            max-width: 700px;
            margin: 0 auto 3rem;
            font-size: 1.2rem;
        }

        .cta-buttons {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
        }

        .btn-dark {
            background: var(--black);
            color: var(--gold);
            border: 2px solid var(--black);
        }

        .btn-dark:hover {
            background: transparent;
            color: var(--black);
            transform: translateY(-3px);
        }

        /* **Footer (Gold Accents) ** */
        footer {
            background: var(--darker-bg);
            padding: 6rem 0 3rem;
            border-top: 1px solid rgba(255, 215, 0, 0.1);
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 3rem;
        }

        .footer-col h3 {
            font-size: 1.5rem;
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
            height: 3px;
            background: var(--gold);
        }

        .footer-col p {
            color: var(--text-light);
            margin-bottom: 1.5rem;
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 1rem;
        }

        .footer-links a {
            color: var(--text-light);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }

        .footer-links a:hover {
            color: var(--gold);
            transform: translateX(5px);
        }

        .footer-links a i {
            color: var(--gold);
            font-size: 0.9rem;
        }

        .footer-social {
            display: flex;
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .footer-social-link {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--gold);
            font-size: 1.2rem;
            transition: var(--transition);
        }

        .footer-social-link:hover {
            background: var(--gold);
            color: var(--black);
            transform: translateY(-3px);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 3rem;
            border-top: 1px solid rgba(255, 215, 0, 0.1);
            color: var(--text-light);
            font-size: 0.95rem;
        }

        /* **Back to Top (Gold Button) ** */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 60px;
            height: 60px;
            background: var(--gold);
            color: var(--black);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
            z-index: 99;
            box-shadow: 0 8px 30px rgba(255, 215, 0, 0.3);
            font-size: 1.3rem;
        }

        .back-to-top.active {
            opacity: 1;
            visibility: visible;
        }

        .back-to-top:hover {
            transform: translateY(-5px) scale(1.1);
        }

        /* **Responsive Design ** */
        @media (max-width: 1200px) {
            .hero h1 {
                font-size: 3rem;
            }
            .section-header h2 {
                font-size: 2.5rem;
            }
        }

        @media (max-width: 992px) {
            .hero-content, .journey-content {
                flex-direction: column;
                gap: 3rem;
            }
            .hero-text, .journey-text {
                text-align: center;
            }
            .hero p, .journey-text p {
                margin: 0 auto 2rem;
            }
            .hero-buttons, .social-links {
                justify-content: center;
            }
            .timeline::before {
                left: 30px;
            }
            .timeline-item, .timeline-item:nth-child(even) {
                justify-content: flex-start;
                padding-left: 70px;
            }
            .timeline-content {
                width: 100%;
            }
            .timeline-content::before {
                left: -10px;
                right: auto;
            }
            .featured-post {
                grid-column: span 1;
            }
            .featured-post .blog-image {
                height: 250px;
            }
            .featured-post h3 {
                font-size: 1.5rem;
            }
        }

        @media (max-width: 768px) {
          
            .hero h1 {
                font-size: 2.5rem;
            }
            .hero h2 {
                font-size: 1.5rem;
            }
            .section-header h2 {
                font-size: 2.2rem;
            }
            .blog-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 1rem;
                position:relative;
            }
            .blog-header p {
                text-align: left;
            }
            .cta h2 {
                font-size: 2.5rem;
            }
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
            .blog-tabs {
                justify-content: flex-start;
            }
        }

        @media (max-width: 576px) {
            .hero {
                padding: 6rem 0 4rem;
            }
            .hero h1 {
                font-size: 2.2rem;
            }
            .hero h2 {
                font-size: 1.3rem;
            }
            .hero-buttons {
                flex-direction: column;
            }
            .section-header h2 {
                font-size: 2rem;
            }
            .blog-grid {
                grid-template-columns: 1fr;
            }
            .cta h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <section class="hero">
        <div class="hero-content">
            <div class="hero-text">
                <h1>
                    <span class="name-part">Samarjeet</span>
                    <span class="name-part">Kumar</span>
                    <span class="name-part">Singh</span>
                </h1>
                <h2>Founder & CEO of TestUrSelf</h2>
                <p>Educator | IISc Bengaluru | BOD, Kartavya | Materials Engineering</p>
                
                <div class="hero-buttons">
                    <a href="#blog" class="btn btn-primary">Read My Blog</a>
                    <a href="#journey" class="btn btn-outline">My Journey</a>
                </div>
                
                <div class="social-links">
                    <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-linkedin-in"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            
            <div class="hero-image">
                <img src="https://images-website-testurself.s3.us-east-1.amazonaws.com/bloghomepic.png" alt="Samarjeet Kumar Singh">
            </div>
        </div>
    </section>

    <!-- **My Journey Section (Timeline) ** -->
    <section class="journey" id="journey">
        <div class="container">
            <div class="section-header">
                <h2>My Journey</h2>
                <p>From GATE aspirant to creating India's most trusted GATE MT & XE preparation platform</p>
            </div>
            
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-year">2016</div>
                        <h3 class="timeline-title">AIR 7 in GATE</h3>
                        <p class="timeline-desc">Secured All India Rank 7 in GATE, paving the way for my M.Tech at IISc Benguluru.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-year">2017</div>
                        <h3 class="timeline-title">Teaching Passion</h3>
                        <p class="timeline-desc">Started mentoring GATE aspirants and realized the gaps in the Metallurgical Engineering stream.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-year">2017</div>
                        <h3 class="timeline-title">Founded TestUrSelf</h3>
                        <p class="timeline-desc">Launched TestUrSelf with a vision to make quality GATE preparation accessible to all.</p>
                    </div>
                </div>
                
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-year">2025</div>
                        <h3 class="timeline-title">17,000+ Students</h3>
                        <p class="timeline-desc">TestUrSelf became India's fastest-growing GATE MT and XE platform, with 460+ toppers in the Top 100.</p>
                    </div>
                </div>
            </div>
            
            <div class="journey-stats">
                <div class="stat-card">
                    <div class="stat-number">17K+</div>
                    <div class="stat-label">Registered Students</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">460+</div>
                    <div class="stat-label">GATE Toppers in Top 100</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">8+</div>
                    <div class="stat-label">Years Experience</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">8+</div>
                    <div class="stat-label">AIR 1 in GATE</div>
                </div>
            </div>
        </div>
    </section>

    <!-- **Enhanced Blog Section with Tabs ** -->
    <section class="blog" id="blog">
        <div class="container">
            <div class="blog-header">
                <div class="section-header">
                    <h2>My Latest Articles</h2>
                    <p>Sharing insights on GATE preparation, education technology, and career growth</p>
                </div>
              
            </div>
            
            <!-- Blog Tabs -->
            <div class="blog-tabs">
                <div class="blog-tab active" data-category="all">All Articles</div>
                <div class="blog-tab" data-category="gate">GATE Preparation</div>
                <div class="blog-tab" data-category="edtech">EdTech Insights</div>
                <div class="blog-tab" data-category="career">Career Guidance</div>
                <div class="blog-tab" data-category="entrepreneurship">Entrepreneurship</div>
            </div>
            
            <!-- Blog Grid -->
            <div class="blog-grid">
                <!-- Featured Post -->
                <article class="blog-card featured-post" data-category="edtech">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Future of EdTech">
                        <span class="blog-category">GATE</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> March 15, 2025</span>
                            <span><i class="far fa-eye"></i> 8.7K Views</span>
                            <span><i class="far fa-comment"></i> 42 Comments</span>
                        </div>
                        <h3>My 8 Months Gate Metallurgy Preparation Strategy</h3>
                        <p>Hey there! I just wanted to share my journey to cracking GATE Metallurgy with AIR-7. It wasn’t easy, but with 8 months of intense preparation, strong concepts, PYQs, and regular mocks, I finally achieved my goal. Consistency, revision, and a smart strategy were key to my success. Good luck on your own GATE Metallurgy journey.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">GATE</span>
                            <span class="blog-tag">Metallurgy</span>
                            <span class="blog-tag">Exam</span>
                            <span class="blog-tag">TestUrSelf</span>
                        </div>
                        <a target="blank" href="https://blog.gometallurgy.in/blog/2025/My-8-Months-GATE-Metallurgy-Preparation-Strategy/" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <!-- GATE Preparation Post -->
                <article class="blog-card" data-category="gate">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1588072432836-e10032774350?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="GATE Strategy">
                        <span class="blog-category">GATE</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> May 28, 2025</span>
                            <span><i class="far fa-eye"></i> 12.3K Views</span>
                            <span><i class="far fa-comment"></i> 87 Comments</span>
                        </div>
                        <h3>My 6-Month GATE Preparation Strategy</h3>
                        <p>The exact roadmap I followed to secure AIR 32 in GATE, including study schedules, key resources, and mindset techniques that can help you achieve similar success.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">GATE</span>
                            <span class="blog-tag">Strategy</span>
                            <span class="blog-tag">Success</span>
                            <span class="blog-tag">Study Plan</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <!-- Entrepreneurship Post -->
                <article class="blog-card" data-category="entrepreneurship">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Entrepreneurship">
                        <span class="blog-category">Entrepreneurship</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> April 22, 2025</span>
                            <span><i class="far fa-eye"></i> 5.4K Views</span>
                            <span><i class="far fa-comment"></i> 23 Comments</span>
                        </div>
                        <h3>From Engineer to Entrepreneur</h3>
                        <p>My journey of building TestUrSelf from a small coaching initiative to India's premier GATE platform, including the challenges and lessons learned along the way.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">Entrepreneurship</span>
                            <span class="blog-tag">Startup</span>
                            <span class="blog-tag">Journey</span>
                            <span class="blog-tag">Lessons</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <!-- Career Guidance Post -->
                <article class="blog-card" data-category="career">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Career Paths">
                        <span class="blog-category">Career</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> March 15, 2025</span>
                            <span><i class="far fa-eye"></i> 9.1K Views</span>
                            <span><i class="far fa-comment"></i> 34 Comments</span>
                        </div>
                        <h3>Engineering Career Paths After GATE</h3>
                        <p>A comprehensive guide to the various career opportunities available after GATE, including PSU jobs, higher education abroad, research opportunities, and more.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">Career</span>
                            <span class="blog-tag">GATE</span>
                            <span class="blog-tag">Opportunities</span>
                            <span class="blog-tag">PSU</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <!-- EdTech Post -->
                <article class="blog-card" data-category="edtech">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1546410531-bb4caa6b424d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1471&q=80" alt="Personalized Learning">
                        <span class="blog-category">EdTech</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> February 28, 2025</span>
                            <span><i class="far fa-eye"></i> 6.8K Views</span>
                            <span><i class="far fa-comment"></i> 19 Comments</span>
                        </div>
                        <h3>The Power of Personalized Learning</h3>
                        <p>How adaptive learning technologies are transforming education and why one-size-fits-all approaches are becoming obsolete in the digital age.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">EdTech</span>
                            <span class="blog-tag">Learning</span>
                            <span class="blog-tag">Technology</span>
                            <span class="blog-tag">Adaptive</span>
                        </div>
                        <a href="#" class="read-more">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>
                    </div>
                </article>
                
                <!-- GATE Preparation Post -->
                <article class="blog-card" data-category="gate">
                    <div class="blog-image">
                        <img src="https://images.unsplash.com/photo-1434030216411-0b793f4b4173?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Time Management">
                        <span class="blog-category">GATE</span>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> January 10, 2025</span>
                            <span><i class="far fa-eye"></i> 11.2K Views</span>
                            <span><i class="far fa-comment"></i> 45 Comments</span>
                        </div>
                        <h3>Time Management for GATE Aspirants</h3>
                        <p>Proven techniques to maximize your study efficiency, balance preparation with college/work, and make the most of your limited time before the exam.</p>
                        <div class="blog-tags">
                            <span class="blog-tag">GATE</span>
                            <span class="blog-tag">Time Management</span>
                            <span class="blog-tag">Productivity</span>
                            <span class="blog-tag">Study Tips</span>
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

    <!-- **Testimonials (Interactive Cards) ** -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-header">
                <h2>What People Say</h2>
                <p>Testimonials from students, colleagues, and industry leaders</p>
            </div>
            
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://images-website-testurself.s3.us-east-1.amazonaws.com/AIR-1-2020.png" alt="Jaya Gupta">
                        </div>
                        <div class="testimonial-info">
                            <h4>Jaya Gupta</h4>
                            <p>GATE 2020 AIR 1</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="testimonial-text">
                        "The test series of TestUrSelf was extremely helpful in my GATE Metallurgy preparation. It helped me analyze my weak and strong areas, and the platform closely simulated the actual GATE exam environment. The wide range of questions—from easy to tough—strengthened my problem-solving ability and built the mental resilience needed for any type of paper. A special thanks to Samarjeet Sir for his constant guidance and for designing such a well-structured and doubt-clearing test series."
                    </p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://images-website-testurself.s3.us-east-1.amazonaws.com/1587805066557.jpeg" alt="Dr. Priya Patel">
                        </div>
                        <div class="testimonial-info">
                            <h4>Dr. Chinmay Dahale</h4>
                            <p>Professor, IISc Banglore, TCS research</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="testimonial-text">
                        "TestUrSelf is a fantastic and well growing organization. Samarjeet sir personally helped me a lot in order to solve my doubts. Many of the questions from test series was repeated in the GATE exam. So, I recommend TestUrSelf online test series to every gate aspirant."
                    </p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">
                            <img src="https://images-website-testurself.s3.us-east-1.amazonaws.com/B71CD8BB-22E7-4555-9AB7-CF185DA4272C.jpeg" alt="Amit Singh">
                        </div>
                        <div class="testimonial-info">
                            <h4>Ravi kumar Singh</h4>
                            <p>IISc, Program Lead at ExxonMobil</p>
                        </div>
                    </div>
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <p class="testimonial-text">
                        "TestUrSelf is one of the best platforms to gear up for GATE Metallurgy. The test series is structured so well that with each test, your confidence naturally builds up. It also helps you master effective time management during exams. I’ve been closely associated with this organization for the past two years and have witnessed its exceptional growth firsthand. I strongly recommend undergraduate students to start their GATE preparation early and take full advantage of what TestUrSelf has to offer."
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- **CTA Section (Gold Gradient) ** -->
    <section class="cta">
        <div class="container cta-content">
            <h2>Join My GATE 2026 Masterclass</h2>
            <p>Get exclusive access to my personal strategies, study techniques, and mentorship to achieve your GATE goals.</p>
            
            <div class="cta-buttons">
                <a href="#" class="btn btn-dark">Enroll Now</a>
                <a href="#" class="btn btn-outline-black">Learn More</a>
            </div>
        </div>
    </section>

    <!-- **Footer (Gold Accents) ** -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>About Me</h3>
                    <p>Education entrepreneur passionate about transforming engineering education in India.</p>
                    <div class="footer-social">
                        <a href="#" class="footer-social-link"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="footer-social-link"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="footer-social-link"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="footer-social-link"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Home</a></li>
                        <li><a href="#journey"><i class="fas fa-chevron-right"></i> My Journey</a></li>
                        <li><a href="#blog"><i class="fas fa-chevron-right"></i> Blog</a></li>
                        <li><a href="#testimonials"><i class="fas fa-chevron-right"></i> Testimonials</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Popular Articles</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> GATE Strategy</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> EdTech Trends</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Career Paths</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Entrepreneurship</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Contact Me</h3>
                    <p><i class="fas fa-map-marker-alt"></i> TestUrSelf HQ, Bangalore</p>
                    <p><i class="fas fa-phone-alt"></i> +91 9876543210</p>
                    <p><i class="fas fa-envelope"></i> samarjeet@testurself.com</p>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2025 Samarjeet Kumar Singh. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- **Back to Top (Gold Button) ** -->
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
                    
                    // Close mobile menu if open
                    if (nav.classList.contains('active')) {
                        nav.classList.remove('active');
                    }
                }
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

        // Animation on Scroll
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.hero-image, .timeline-content, .blog-card, .testimonial-card, .section-header');
            
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
        document.querySelectorAll('.hero-image, .timeline-content, .blog-card, .testimonial-card, .section-header').forEach(element => {
            element.style.opacity = '0';
            element.style.transform = 'translateY(30px)';
            element.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
        });

        // Run animation check on load and scroll
        window.addEventListener('load', animateOnScroll);
        window.addEventListener('scroll', animateOnScroll);

        // Blog Tab Filtering
        const blogTabs = document.querySelectorAll('.blog-tab');
        const blogCards = document.querySelectorAll('.blog-card');
        
        blogTabs.forEach(tab => {
            tab.addEventListener('click', () => {
                // Remove active class from all tabs
                blogTabs.forEach(t => t.classList.remove('active'));
                // Add active class to clicked tab
                tab.classList.add('active');
                
                const category = tab.dataset.category;
                
                // Filter blog cards
                blogCards.forEach(card => {
                    if (category === 'all' || card.dataset.category === category) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        });

        // Name Animation on Hover
        const nameParts = document.querySelectorAll('.name-part');
        
        nameParts.forEach((part, index) => {
            part.addEventListener('mouseover', () => {
                // Add a slight delay based on index for a wave effect
                part.style.transitionDelay = `${index * 0.1}s`;
            });
            
            part.addEventListener('mouseout', () => {
                part.style.transitionDelay = '0s';
            });
        });
    </script>
</body>
</html>
