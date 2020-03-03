---
title: 과제 개요
feature_text: |
  ## Griffin-Edge
  10msec 미만의 서비스 응답 속도를 보장하는 초저지연 지능형 클라우드 엣지 SW 플랫폼 핵심 기술 개발
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "지능형 클라우드 엣지 SW 플랫폼은 대규모 엣지 단말들이 생성하는 방대한 데이터의 중앙 클라우드 집중화로 인한 처리 및 전송 지연 극복을 위해 단말 근접 위치에서 데이터를 처리하고, 중앙 클라우드-엣지-단말 간 분산 협업을 기반으로 응답 속도 민감형 서비스를 지원하는 클라우드 엣지 플랫폼 기술"
layout: page
---

지능형 클라우드 엣지 SW 플랫폼은 대규모 엣지 단말들이 생성하는 방대한 데이터의 중앙 클라우드 집중화로 인한 처리 및 전송 지연 극복을 위해 단말 근접 위치에서 데이터를 처리하고, 중앙 클라우드-엣지-단말 간 분산 협업을 기반으로 응답 속도 민감형 서비스를 지원하는 클라우드 엣지 플랫폼 기술


## 개념도


## 연구 내용

##### 1. 지능형 클라우드 엣지 플랫폼의 자율 구성 및 통합 관리 기술
 - 적용 시스템 규모에 따른 가변형 클라우드 엣지 플랫폼 구성 기술
##### 2. 데이터의 초저지연 처리를 위한 고속 클라우드 엣지 플랫폼 기술
##### 3. 중앙클라우드-클라우드엣지(엣지), 엣지-엣지 간 협업을 위한 서비스 프레임워크 기술
##### 4. 클라우드 엣지 기반의 지능형 서비스 운용 최적화 지원 기술
##### 5. 클라우드 엣지 컴퓨팅 기반 기술 표준 개발
##### 6. 지능형 클라우드 엣지 SW 플랫폼의 활용 사례 PoC 발굴 및 검증

# ## Installation

### Quick setup

To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

- ⚗️🍨 Vanilla Jekyll starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-kit){:style="background: none"}
- ⚗️🌲 Forestry starter kit  
  [![Deploy to Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=daviddarnes/alembic-forestry-kit&engine=jekyll){:style="background: none"}  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-forestry-kit){:style="background: none"}
- ⚗️💠 Netlify CMS starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-netlifycms-kit&stack=cms){:style="background: none"}

- ⚗️:octocat: GitHub Pages with remote theme kit  
  {% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}
- ⚗️🚀 Stackbit starter kit  
  [![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/daviddarnes/alembic-stackbit-kit){:style="background: none"}

### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, simply by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
