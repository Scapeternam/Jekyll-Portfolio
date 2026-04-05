---
layout: page
title: Mes Projets
background: grey
permalink: /projets/
---

<div class="container">
    <div class="row">
        <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Mes Réalisations</h2>
            <h3 class="section-subheading text-muted">Des projets concrets, de l'idée à la production.</h3>
        </div>
    </div>

    <!-- HealthMate -->
    <div class="row mb-5 align-items-center">
        <div class="col-md-6 text-center">
            <img src="{{ '/assets/img/portfolio/logo-healthmate.png' | relative_url }}" alt="Logo HealthMate" class="img-fluid" style="max-width: 280px; border-radius: 16px;">
        </div>
        <div class="col-md-6">
            <h3>HealthMate</h3>
            <p class="text-muted"><strong>SaaS freemium — Compagnon médical IA</strong></p>
            <p>Plateforme médicale avec diagnostic IA (1 gratuit, 9,90 €/mois illimité). Architecture monorepo sécurisée conforme aux normes HDS et RGPD.</p>
            <ul class="text-muted">
                <li>Next.js 14 App Router + Fastify v5 (API)</li>
                <li>PostgreSQL, Prisma ORM, Redis</li>
                <li>Chiffrement AES-256-GCM des données patients</li>
                <li>Authentification JWT + MFA TOTP</li>
                <li>Paiement Stripe, IA Anthropic Claude</li>
            </ul>
        </div>
    </div>

    <hr>

    <!-- PickUp -->
    <div class="row mb-5 align-items-center">
        <div class="col-md-6 text-center">
            <img src="{{ '/assets/img/portfolio/logo-pickup.png' | relative_url }}" alt="Logo PickUp" class="img-fluid" style="max-width: 280px; border-radius: 16px;">
        </div>
        <div class="col-md-6">
            <h3>PickUp</h3>
            <p class="text-muted"><strong>Marketplace de services urbains on-demand</strong></p>
            <p>Plateforme couvrant 19 types de missions : courses, conciergerie, photo et B2B. Modèle driver-first avec répartition transparente 85/15.</p>
            <ul class="text-muted">
                <li>React 18, Tailwind CSS, shadcn/ui</li>
                <li>Base44 (BaaS), Stripe Connect</li>
                <li>3 portails : Particulier, Pro, Livreur</li>
                <li>POD sécurisé (QR Code + PIN + photo)</li>
                <li>Design system complet, mobile-first</li>
            </ul>
        </div>
    </div>

    <hr>

    <!-- FrontalierPro -->
    <div class="row mb-5 align-items-center">
        <div class="col-md-6 text-center">
            <img src="{{ '/assets/img/portfolio/logo-frontalierpro.jpg' | relative_url }}" alt="Logo FrontalierPro" class="img-fluid" style="max-width: 280px; border-radius: 16px;">
        </div>
        <div class="col-md-6">
            <h3>FrontalierPro</h3>
            <p class="text-muted"><strong>SaaS — Plateforme pour travailleurs frontaliers</strong></p>
            <p>Plateforme de services dédiée aux travailleurs transfrontaliers, simplifiant leurs démarches quotidiennes et leur accès aux services spécialisés.</p>
            <ul class="text-muted">
                <li>Plateforme SaaS complète</li>
                <li>Services spécialisés frontaliers</li>
                <li>Interface intuitive et accessible</li>
            </ul>
            <a class="btn btn-primary" href="https://frontalierpro.com" target="_blank">Voir le site</a>
        </div>
    </div>
</div>
