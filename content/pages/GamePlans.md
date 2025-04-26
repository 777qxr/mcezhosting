---
type: PageLayout
title: GamePlans
sections:
  - type: PricingSection
    title:
      type: TitleBlock
      text: Budget Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is the subtitle for the pricing section
    plans:
      - type: PricingPlan
        title: Starter Plan
        price: Newbie
        details: per month
        description: |
          Server Specification
        features:
          - ₱350/month
          - 4GB RAM
          - 4 Cores CPU
          - 100 GB DISK
          - 3 BACKUP SLOTS
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
        actions:
          - type: Button
            label: Get Now
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: Starter Plan
        price: World
        details: per month
        description: |
          Server Specification
        features:
          - ₱580/month
          - 8 GB RAM
          - 4 Cores CPU
          - 100 GB DISK
          - 3 BACKUP SLOTS
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Get Now
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: Starter Plan
        price: Tree
        details: per month
        description: |+
          Server Specification

        features:
          - ₱640/month
          - 16 GB RAM
          - 6 Cores CPU
          - 200 GB DISK
          - 3 BACKUP SLOTS
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
        actions:
          - type: Button
            label: Get Now
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: GamePlans
seo:
  type: Seo
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
