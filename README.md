# Code Repository Standards

In an effort to make onboarding journey for a new developer less painful and for a fresh developer joining a long running project much easier, code repository takes an important role for this. It should be not only as a place to store source codes, but a technical documentation for every developer to refer to.

## Table of Contents
* [Repository Name](#repository-name)
* [Repository Description](#repository-description)

## Repository Name

### Why

From time to time, developers refer to an old project as a reference when working on a new and similar one, hence repositories should be easy to search by its name, clear and self-explanatory.

### Convention

- It should be all in lowercase
- It should be in snake case, using underscore (`_`). Correct: `bcaf_vmall`. Wrong: `BCAF-vmall`
- For project based repository from a recurring client, it should start with the known short code of the client name, such as `bcaf` for BCA Finance, `bcad` for BCA Digital, `alto` for Alto, and so on. Ideally this should be in sync with the client code in CRM used by other departments such as Finance or Project Managers.
- The second part should be the known code name of the project. For example `vmall` for Virtual Mall, `hellogod` for Hello God application and so on. Again, this should be in sync with the client code in CRM used by other departments.
- The next part should be the domain specific part of the project. For example `backend` for Backend part, `frontend` for web application part, `mobile` for mobile app developed using hybrid framework such as Flutter or React Native, `android` and `ios` each for mobile app developed in native.

## Repository Description

### Why

Repository name is limited in character (40 characters max in Github), so description (or Project Description in Gitlab) is the best way to explain in brief about the repository while it's still searchable and showing in search results.

### Convention

- It should at least explain the repository name. For example, the description for `bcaf_vmall_backend` repository should be "**BCA Finance Virtual Mall Backend**" at the minimum, this way at least we know what `bcaf` or `vmall` stands for.
- It should contains the main technology or framework used. For example, "**BCA Finance Virtual Mall Backend Using Spring Boot**", this way we can easily search repository based on major framework or technology such as Spring Boot, Laravel, Angular JS, Flutter and so on.
- If necessary put the programming language used to differentiate with other. For example put Kotlin to differentiate with other project using Java, or put Swift to differentiate with other project using Objective C.
