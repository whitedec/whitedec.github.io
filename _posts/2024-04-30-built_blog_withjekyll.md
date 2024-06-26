---
layout: post
title:  "깃허브에서 Jekyll을 사용한 블로그만들기!"
date:   2024-04-30 13:02:00 +0900
categories: Jekyll
---
## 초심자가 깃허브를 이용하여 블로그를 만든다면?

### Jekyll 소개 및 다른 유명한 프로그램

Jekyll은 정적 웹사이트와 블로그를 만들기 위한 간단하면서도 확장 가능한 도구입니다. 이 프로그램은 템플릿과 마크다운 파일을 사용하여 컨텐츠를 작성하고 정적 HTML 웹사이트로 변환합니다. GitHub Pages와의 통합으로 인해, Jekyll은 무료로 호스팅되는 블로그나 웹사이트를 빠르게 배포할 수 있으며, 설정이 간단하고 사용하기 쉽습니다.

Jekyll과 유사하거나 더 인기 있는 다른 프로그램들은 다음과 같습니다:

1. Hugo - Hugo는 Jekyll과 비슷한 정적 사이트 생성기이지만, Go 언어로 작성되어 있어 훨씬 빠른 빌드 시간을 자랑합니다. 큰 프로젝트에 적합하며, 다양한 테마와 확장 기능을 제공합니다.
11. Gatsby - React를 기반으로 하는 또 다른 정적 사이트 생성기로, 웹사이트를 정적 파일로 컴파일하면서도 클라이언트 측에서 동적인 웹 앱의 혜택을 누릴 수 있습니다. Gatsby는 풍부한 플러그인 생태계와 함께 뛰어난 성능 최적화를 제공합니다.
1. Next.js - 서버 사이드 렌더링(SSR)을 지원하는 React 프레임워크입니다. 정적 사이트 생성(SSG) 기능도 제공하며, 더 동적인 웹사이트와 애플리케이션을 구축할 수 있습니다. SEO와 초기 로딩 성능을 개선할 수 있는 강력한 도구입니다.
1. Hexo - Node.js 기반의 빠른 정적 사이트 생성기로, 특히 블로그에 최적화되어 있습니다. Markdown을 사용하고 GitHub Pages와 쉽게 통합됩니다.

각 도구는 특정 사용 사례와 개발자의 요구에 따라 장단점이 있으니, 프로젝트의 요구 사항에 가장 적합한 도구를 선택하는 것이 중요합니다.

### 깃허브를 이용하여 블로그를 만든다면 역시 Jekyll

깃허브를 이용하여 블로그를 만들 계획이라면 Jekyll을 추천합니다. Jekyll은 GitHub Pages와의 통합이 매우 잘 되어 있어서 GitHub에서 직접 호스팅할 수 있으며, 설정이 간단합니다. Jekyll은 마크다운을 사용하여 콘텐츠를 작성하고, 사전에 정의된 템플릿을 통해 HTML로 변환하는 방식으로 작동합니다.

**Jekyll의 장점**은 다음과 같습니다:

1. 간편한 설정: GitHub 계정에 레포지토리를 만들고 Jekyll 테마를 선택한 후 몇 가지 설정만으로 블로그를 시작할 수 있습니다.
1. 무료 호스팅: GitHub Pages를 통해 무료로 호스팅되므로 호스팅 비용이 들지 않습니다.1. Preview your site locally
You can preview your site by starting a Jekyll server locally. This is a very important and convenient feature. It takes a few seconds to several minutes to make corrections or create new content, send it to the server, and check for updates. If you try it, you will see that this is a bit inconvenient. Therefore, it is recommended to first check the posting on your local server and then push using git. To do this, use the following command:


1. GitHub 계정을 만듭니다.
1. 새로운 레포지토리를 생성하고 Jekyll 테마를 선택합니다.
1. _posts 폴더에 마크다운 파일을 추가하여 블로그 포스트를 작성합니다.
1. 설정을 커스터마이즈하여 블로그의 모습을 변경할 수 있습니다.

이러한 이유로 Jekyll은 깃허브를 이용하여 처음으로 블로그를 시작하는 초심자에게 적합한 선택입니다.

다음 포스트는 Jekyll로 github에서 블로그를 만들기로 결정했다면 그 다음에 해야할 일을 차근차근 단계별로 설명해 보겠습니다. 