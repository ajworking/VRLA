/* Mobile First Responsive Design */
        @media (max-width: 768px) {
            body {
                background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
                padding: 10px;
            }

            .container {
                margin: 0;
                border-radius: 15px;
                box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            }

            header {
                padding: 1.5rem 1rem;
            }

            h1 {
                font-size: 1.8rem;
                margin-bottom: 0.3rem;
            }

            .subtitle {
                font-size: 1rem;
            }

            nav {
                padding: 0.5rem;
            }

            .nav-buttons {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                gap: 0.5rem;
                max-width: 400px;
                margin: 0 auto;
            }

            .nav-btn {
                width: 100%;
                padding: 10px 16px;
                font-size: 0.9rem;
                border-radius: 20px;
            }

            .content {
                padding: 1rem;
            }

            h2 {
                font-size: 1.5rem;
                margin-bottom: 1rem;
            }

            h3 {
                font-size: 1.2rem;
                margin: 1rem 0 0.8rem 0;
            }

            .grid-container {
                grid-template-columns: 1fr;
                gap: 1rem;
                margin: 1.5rem 0;
            }

            .card {
                padding: 1.2rem;
                border-radius: 12px;
            }

            .highlight-box {
                padding: 1.2rem;
                margin: 1.2rem 0;
                border-radius: 8px;
            }

            .stats-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 0.8rem;
                margin: 1.5rem 0;
            }

            .stat-card {
                padding: 1.2rem 0.8rem;
                border-radius: 12px;
            }

            .stat-number {
                font-size: 1.5rem;
            }

            .future-trends {
                padding: 1.5rem;
                margin: 1.5rem 0;
                border-radius: 12px;
            }

            .timeline::before {
                left: 15px;
                width: 2px;
            }

            .timeline-item {
                width: calc(100% - 40px);
                left: 40px !important;
                text-align: left !important;
                margin: 1.5rem 0;
                padding: 0 1rem;
            }

            .timeline-content {
                padding: 1.2rem;
                border-radius: 12px;
            }

            .timeline-content::before {
                content: '';
                position: absolute;
                left: -25px;
                top: 20px;
                width: 12px;
                height: 12px;
                background: #667eea;
                border-radius: 50%;
                border: 3px solid white;
                box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
            }

            .timeline-year {
                font-size: 1.1rem;
            }

            p {
                text-align: left;
                font-size: 0.95rem;
                line-height: 1.5;
            }

            ul {
                margin: 0.8rem 0 0.8rem 1.5rem;
            }

            li {
                margin-bottom: 0.4rem;
                font-size: 0.95rem;
            }
        }

        /* Small mobile devices */
        @media (max-width: 480px) {
            body {
                padding: 5px;
            }

            .container {
                border-radius: 12px;
            }

            header {
                padding: 1.2rem 0.8rem;
            }

            h1 {
                font-size: 1.6rem;
            }

            .subtitle {
                font-size: 0.9rem;
            }

            .nav-buttons {
                grid-template-columns: 1fr;
                gap: 0.4rem;
            }

            .nav-btn {
                padding: 12px 20px;
                font-size: 0.9rem;
            }

            .content {
                padding: 0.8rem;
            }

            h2 {
                font-size: 1.3rem;
            }

            h3 {
                font-size: 1.1rem;
            }

            .stats-grid {
                grid-template-columns: 1fr;
            }

            .stat-card {
                padding: 1rem;
            }

            .card {
                padding: 1rem;
            }

            .highlight-box {
                padding: 1rem;
            }

            .future-trends {
                padding: 1.2rem;
            }

            .timeline-item {
                width: calc(100% - 30px);
                left: 30px !important;
                padding: 0 0.8rem;
            }
        }

        /* Large mobile/small tablet */
        @media (min-width: 769px) and (max-width: 1024px) {
            .container {
                margin: 15px;
            }

            .nav-buttons {
                gap: 0.8rem;
            }

            .nav-btn {
                padding: 10px 20px;
                font-size: 0.95rem;
            }

            .grid-container {
                grid-template-columns: repeat(2, 1fr);
                gap: 1.5rem;
            }

            .stats-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
