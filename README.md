# Storybook practice

Storybook은 UI개발 도구입니다. 구성 요소를 분리하여 개발을 더 빠르고 쉽게 만듭니다.
한 번에 하나의 구성 요소에서 작업할 수 있습니다.
복잡한 개발 스택을 시작하거나 특정 데이터를 데이터베이스에 강제로 넣거나 애프리케이션을 탐색할 필요 없이 전체 UI를 개발할 수 있습니다.

Storybook을 사용하여 웹 애플리케이션에서 작은 원자 구성 요소와 복잡한 페이지를 구축합니다. Storybook을 사용한다면 Atomic Design을 위한 강력한 툴이라 생각합니다.

## 설치

Storybook 전용 프로젝트 Storybook 전용으로 프로젝트를 구성하면 더욱 편리할거라 생각듭니다.

```
mkdir [폴더 명]
cd [폴더 명]
yarn init -y 또는 npm init -y
npx -p @storybook/cli sb init --type react
yarn add react react-dom
```
