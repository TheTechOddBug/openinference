:robot: I have created a release *beep* *boop*
---


<details><summary>python-openinference-semantic-conventions: 0.1.27</summary>

## [0.1.27](https://github.com/TheTechOddBug/openinference/compare/python-openinference-semantic-conventions-v0.1.26...python-openinference-semantic-conventions-v0.1.27) (2026-02-20)


### Features

* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/TheTechOddBug/openinference/issues/2238)) ([d03047d](https://github.com/TheTechOddBug/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/TheTechOddBug/openinference/issues/2242)) ([478d17a](https://github.com/TheTechOddBug/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))
* **semconv:** add prompt span kind and prompt template variables attributes ([#2669](https://github.com/TheTechOddBug/openinference/issues/2669)) ([cd5d2ff](https://github.com/TheTechOddBug/openinference/commit/cd5d2ff13ecbd50472f4097ac10994aee3245924))


### Bug Fixes

* **semconv:** refactor semconv ([#2281](https://github.com/TheTechOddBug/openinference/issues/2281)) ([090864b](https://github.com/TheTechOddBug/openinference/commit/090864b0549588830c38aaa1fcd9c9700f7caf14))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation: 0.1.45</summary>

## [0.1.45](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-v0.1.44...python-openinference-instrumentation-v0.1.45) (2026-02-20)


### Features

* add context manager for capturing openinference spans ([#1781](https://github.com/TheTechOddBug/openinference/issues/1781)) ([aab3386](https://github.com/TheTechOddBug/openinference/commit/aab33868276627705f3e83fe8898429b71a23695))
* add Open Agent Spec Instrumentor ([#2560](https://github.com/TheTechOddBug/openinference/issues/2560)) ([48a8722](https://github.com/TheTechOddBug/openinference/commit/48a87228767089416bbe608a8ff782923c9db5b5))
* Allow to hide llm.prompts span from trace config ([#1863](https://github.com/TheTechOddBug/openinference/issues/1863)) ([7d633d8](https://github.com/TheTechOddBug/openinference/commit/7d633d8fcf6ab5dbd8596a5900f3982db8e88d89))
* increase default span attribute count limit to 10,000 ([#2042](https://github.com/TheTechOddBug/openinference/issues/2042)) ([0e90576](https://github.com/TheTechOddBug/openinference/commit/0e90576cd841c73f561ffbb98d9a39cfe035509d))
* **instrumentation:** add dangerously_using_project context manager ([#2134](https://github.com/TheTechOddBug/openinference/issues/2134)) ([aed9db0](https://github.com/TheTechOddBug/openinference/commit/aed9db05b93d1ae0cb7d8a49977de1926b038740))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/TheTechOddBug/openinference/issues/2238)) ([d03047d](https://github.com/TheTechOddBug/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/TheTechOddBug/openinference/issues/2242)) ([478d17a](https://github.com/TheTechOddBug/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))
* **python:** get_first_span_id via a context manager ([#2013](https://github.com/TheTechOddBug/openinference/issues/2013)) ([b0b080c](https://github.com/TheTechOddBug/openinference/commit/b0b080c564a2fb72b8f6796cad603f0166bcc767))


### Bug Fixes

* Enable sampling when using OpenInference tracer ([#1782](https://github.com/TheTechOddBug/openinference/issues/1782)) ([b4007cf](https://github.com/TheTechOddBug/openinference/commit/b4007cffc5857028d6004aebd369877cab96d801))
* **instrumentation:** update openinference span kind helper to include prompt ([#2672](https://github.com/TheTechOddBug/openinference/issues/2672)) ([6603d44](https://github.com/TheTechOddBug/openinference/commit/6603d444d5a36aa661908da24ce6e9d1c78bc1fe))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* version upper bound on wrapt &lt;2.0 ([#2325](https://github.com/TheTechOddBug/openinference/issues/2325)) ([57a4fa3](https://github.com/TheTechOddBug/openinference/commit/57a4fa3329327bea41d6498c992d32ad87fd334c))
</details>

<details><summary>python-openinference-instrumentation-agentspec: 0.1.1</summary>

## [0.1.1](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-agentspec-v0.1.0...python-openinference-instrumentation-agentspec-v0.1.1) (2026-02-20)


### Features

* add Open Agent Spec Instrumentor ([#2560](https://github.com/TheTechOddBug/openinference/issues/2560)) ([48a8722](https://github.com/TheTechOddBug/openinference/commit/48a87228767089416bbe608a8ff782923c9db5b5))
</details>

<details><summary>python-openinference-instrumentation-agno: 0.1.29</summary>

## [0.1.29](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-agno-v0.1.28...python-openinference-instrumentation-agno-v0.1.29) (2026-02-20)


### Features

* add updates for agno 2.5 release ([#2716](https://github.com/TheTechOddBug/openinference/issues/2716)) ([d32092e](https://github.com/TheTechOddBug/openinference/commit/d32092e0d2060feee4e230ee5d0b3644aa925d22))
* **agno:** add workflow wrapper for instrumentation ([#2450](https://github.com/TheTechOddBug/openinference/issues/2450)) ([89699cd](https://github.com/TheTechOddBug/openinference/commit/89699cdc66399e9f61c0880c1fdd62f0101e723d))
* **Agno:** Capture agent graph attributes  ([#2090](https://github.com/TheTechOddBug/openinference/issues/2090)) ([7930348](https://github.com/TheTechOddBug/openinference/commit/7930348788c292958b3701119dc4c2837a341c53))
* **Agno:** Capture graph attributes for agent visual ([#2053](https://github.com/TheTechOddBug/openinference/issues/2053)) ([8d5ae09](https://github.com/TheTechOddBug/openinference/commit/8d5ae09b09fbcfaae7bab0dea25db3a2ad076a4d))
* **agno:** enable user tracking ([#1997](https://github.com/TheTechOddBug/openinference/issues/1997)) ([d76f5f1](https://github.com/TheTechOddBug/openinference/commit/d76f5f1ef112658a8286d9becf8c9f114b7bc911))
* **agno:** remove duplicate constants and resolve tool call issue ([#2304](https://github.com/TheTechOddBug/openinference/issues/2304)) ([2f15069](https://github.com/TheTechOddBug/openinference/commit/2f15069dbda1e0a030f6d095f5156fdd3ae6d2c6))
* enhance function call span attributes with input value and erro& ([#1836](https://github.com/TheTechOddBug/openinference/issues/1836)) ([5d239df](https://github.com/TheTechOddBug/openinference/commit/5d239dfbebcfaf34f276e9169be644b91eeafd09))
* Prioritize subclasses method wrapping to prevent multiple spans ([#1809](https://github.com/TheTechOddBug/openinference/issues/1809)) ([cc37471](https://github.com/TheTechOddBug/openinference/commit/cc37471bcf2be18ff205ab4e49654be42c27daee))
* Updated Agno attributes ([#2262](https://github.com/TheTechOddBug/openinference/issues/2262)) ([a4a2135](https://github.com/TheTechOddBug/openinference/commit/a4a213510a88117cbd0f15c4e84a84c8ee9b470d))


### Bug Fixes

* Agno Session ID issues ([#2313](https://github.com/TheTechOddBug/openinference/issues/2313)) ([34402a0](https://github.com/TheTechOddBug/openinference/commit/34402a0a8478e1b047a76c6a885c5256cec015bc))
* Agno streaming tool call handling ([#2309](https://github.com/TheTechOddBug/openinference/issues/2309)) ([4b7da83](https://github.com/TheTechOddBug/openinference/commit/4b7da833ae9a91989d09ea78c38ca2e0bd44c0b1))
* agno team id release ([#2415](https://github.com/TheTechOddBug/openinference/issues/2415)) ([dcd3aa7](https://github.com/TheTechOddBug/openinference/commit/dcd3aa7f33192a30976485c1a01b06765da24010))
* Agno v2 fixes ([#2211](https://github.com/TheTechOddBug/openinference/issues/2211)) ([278f570](https://github.com/TheTechOddBug/openinference/commit/278f570130635d99672126554b9d3a950c658ff4))
* **agno:** Add agent.name attribute and fix Team span attributes being overwritten by members ([#2516](https://github.com/TheTechOddBug/openinference/issues/2516)) ([4556372](https://github.com/TheTechOddBug/openinference/commit/4556372658fbc55be1f0f7089c2735bb1c57a536))
* **agno:** capture session_id and user_id for teams too ([#2086](https://github.com/TheTechOddBug/openinference/issues/2086)) ([0a51d50](https://github.com/TheTechOddBug/openinference/commit/0a51d50be89a440d6df2fca90fe72ab730ee7267))
* **agno:** multi team runs coming as nested subtraces ([#2533](https://github.com/TheTechOddBug/openinference/issues/2533)) ([ac6576d](https://github.com/TheTechOddBug/openinference/commit/ac6576d6e8c9e69fcf5c0d421770b35ee611b1c9))
* **agno:** Resolving CI issues for Agno ([#2380](https://github.com/TheTechOddBug/openinference/issues/2380)) ([a82ef6c](https://github.com/TheTechOddBug/openinference/commit/a82ef6c34a79d53c892c5017d76cce053655801d))
* **agno:** Update _output_value_and_mime_type to properly deserialize output messages ([#2433](https://github.com/TheTechOddBug/openinference/issues/2433)) ([600d2f3](https://github.com/TheTechOddBug/openinference/commit/600d2f3f320bed94bcae4ae4ed956c2d178a1e1c))
* correct usage of user id & session id ([#2138](https://github.com/TheTechOddBug/openinference/issues/2138)) ([165b7e8](https://github.com/TheTechOddBug/openinference/commit/165b7e890cb9691ff1ab3890288c97dc046f1a1b))
* ensure tool error spans are properly ended and exported ([#2654](https://github.com/TheTechOddBug/openinference/issues/2654)) ([e58f177](https://github.com/TheTechOddBug/openinference/commit/e58f17794f3bde2998dc9f08e1d3307ebd8f96f4))
* Get last run output ([#2369](https://github.com/TheTechOddBug/openinference/issues/2369)) ([57a9758](https://github.com/TheTechOddBug/openinference/commit/57a97585512f34550d5a50508ca801440cda1071))
* Iterators for runs ([#2406](https://github.com/TheTechOddBug/openinference/issues/2406)) ([6ac1483](https://github.com/TheTechOddBug/openinference/commit/6ac14839368a932265cf64b8682586533b1633e2))
* nullable agent.name in agno instrumentation arun ([#1803](https://github.com/TheTechOddBug/openinference/issues/1803)) ([c2cc388](https://github.com/TheTechOddBug/openinference/commit/c2cc3884c3eb2ba00ddb992cc7b2aff1709bd891))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-mistralai: 1.5.0</summary>

## [1.5.0](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-mistralai-v1.4.0...python-openinference-instrumentation-mistralai-v1.5.0) (2026-02-20)


### Features

* **mistralai:** Populate LLM Provider & System Attributes ([#2650](https://github.com/TheTechOddBug/openinference/issues/2650)) ([fbf48ef](https://github.com/TheTechOddBug/openinference/commit/fbf48ef159a9b0f9e0bf3eb46d41a9cfb1cafd44))


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-openai: 0.1.42</summary>

## [0.1.42](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-openai-v0.1.41...python-openinference-instrumentation-openai-v0.1.42) (2026-02-20)


### Features

* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/TheTechOddBug/openinference/issues/2238)) ([d03047d](https://github.com/TheTechOddBug/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* openai + openai agent support custom tool calls ([#2080](https://github.com/TheTechOddBug/openinference/issues/2080)) ([ee8693c](https://github.com/TheTechOddBug/openinference/commit/ee8693c3325380440e4af4e0df708851c5598c30))
* **openai:** align embedding instrumentation with pending spec ([#2210](https://github.com/TheTechOddBug/openinference/issues/2210)) ([df5b9d5](https://github.com/TheTechOddBug/openinference/commit/df5b9d5dc080eddc4c91b6cb413eadb59f6c9982))
* **openai:** implement image redaction for input values when hide_input_images=True ([#2146](https://github.com/TheTechOddBug/openinference/issues/2146)) ([fac0604](https://github.com/TheTechOddBug/openinference/commit/fac0604caeedf0b0332151dfde69f0b51b554652))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/TheTechOddBug/openinference/issues/2242)) ([478d17a](https://github.com/TheTechOddBug/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))


### Bug Fixes

* Openai CI Failures ([#2461](https://github.com/TheTechOddBug/openinference/issues/2461)) ([e2b4dbc](https://github.com/TheTechOddBug/openinference/commit/e2b4dbc32ee797ae89f0814a5c1e48107ccf4dd0))
* **openai:** add tool_id accumulator for resposne ([#2241](https://github.com/TheTechOddBug/openinference/issues/2241)) ([cb6e1a6](https://github.com/TheTechOddBug/openinference/commit/cb6e1a6f68a6262b0eb50d045eef002b086288c4))
* **openai:** handle complex output types in responses API for openai 2 compat ([#2253](https://github.com/TheTechOddBug/openinference/issues/2253)) ([a209e6a](https://github.com/TheTechOddBug/openinference/commit/a209e6a1a33b36a497de5cc44d7059a723a75020))
* **openai:** handle string format for image_url in chat completions ([#2213](https://github.com/TheTechOddBug/openinference/issues/2213)) ([4d09a7e](https://github.com/TheTechOddBug/openinference/commit/4d09a7ec101a849ca74e36820caaff519ebe610e))
* **openai:** update lower bound on openinference-semantic-conventions ([#2279](https://github.com/TheTechOddBug/openinference/issues/2279)) ([45cfad1](https://github.com/TheTechOddBug/openinference/commit/45cfad1d27d247b1a58d08f10db6ed5896863c69))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-openai-agents: 2.0.0</summary>

## [2.0.0](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-openai-agents-v1.4.0...python-openinference-instrumentation-openai-agents-v2.0.0) (2026-02-20)


###   BREAKING CHANGES

* set openinference processor as the exclusive processor by default ([#1792](https://github.com/TheTechOddBug/openinference/issues/1792))

### Features

* Added support py314 ([#2470](https://github.com/TheTechOddBug/openinference/issues/2470)) ([1399bcb](https://github.com/TheTechOddBug/openinference/commit/1399bcba260cc33c07328406c0b6c74466d315ce))
* openai + openai agent support custom tool calls ([#2080](https://github.com/TheTechOddBug/openinference/issues/2080)) ([ee8693c](https://github.com/TheTechOddBug/openinference/commit/ee8693c3325380440e4af4e0df708851c5598c30))
* **openai-agents:** capture graph.node.id and graph.node.parent_id semantics  ([#1854](https://github.com/TheTechOddBug/openinference/issues/1854)) ([0864c13](https://github.com/TheTechOddBug/openinference/commit/0864c13fdfa9e289468ac0a79a2860a155be46de))
* **openai:** implement image redaction for input values when hide_input_images=True ([#2146](https://github.com/TheTechOddBug/openinference/issues/2146)) ([fac0604](https://github.com/TheTechOddBug/openinference/commit/fac0604caeedf0b0332151dfde69f0b51b554652))
* set openinference processor as the exclusive processor by default ([#1792](https://github.com/TheTechOddBug/openinference/issues/1792)) ([d56abb1](https://github.com/TheTechOddBug/openinference/commit/d56abb1935aa4a96925214c39cef045381ab9b15))


### Bug Fixes

* CI issues for openai agents ([#2367](https://github.com/TheTechOddBug/openinference/issues/2367)) ([a18078b](https://github.com/TheTechOddBug/openinference/commit/a18078bb150134b5988c454b9143e1ef93fc4aa6))
* fix IndexError for empty function output ([#1878](https://github.com/TheTechOddBug/openinference/issues/1878)) ([e6453e7](https://github.com/TheTechOddBug/openinference/commit/e6453e72784aac519e05c98b541a551500b814a4))
* Openai CI Failures ([#2461](https://github.com/TheTechOddBug/openinference/issues/2461)) ([e2b4dbc](https://github.com/TheTechOddBug/openinference/commit/e2b4dbc32ee797ae89f0814a5c1e48107ccf4dd0))
* openai-agents CI add eval_type_backport dependency for Python &lt;3.10 compatibility ([#2004](https://github.com/TheTechOddBug/openinference/issues/2004)) ([f38ed8e](https://github.com/TheTechOddBug/openinference/commit/f38ed8efe6734297a3e77c0b4d4ddde32bc8ba11))
* **openai-agents:** handle None token details from providers ([#2496](https://github.com/TheTechOddBug/openinference/issues/2496)) ([aa31202](https://github.com/TheTechOddBug/openinference/commit/aa3120275c228af163bb2d8cba23eca0124610cd))
* **openai-agents:** serialize complex output types to JSON for AttributeValue compatibility ([dc9b1ae](https://github.com/TheTechOddBug/openinference/commit/dc9b1aee75fd2362bf4501bf6f6d267e379d0819))
</details>

<details><summary>python-openinference-instrumentation-vertexai: 0.1.13</summary>

## [0.1.13](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-vertexai-v0.1.12...python-openinference-instrumentation-vertexai-v0.1.13) (2026-02-20)


### Features

* **vertexai:** Populate LLM Provider & System Attributes ([#2617](https://github.com/TheTechOddBug/openinference/issues/2617)) ([321f99a](https://github.com/TheTechOddBug/openinference/commit/321f99a931218045c93e1a1ef346e4963629737e))
</details>

<details><summary>python-openinference-instrumentation-llama-index: 4.3.10</summary>

## [4.3.10](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-llama-index-v4.3.9...python-openinference-instrumentation-llama-index-v4.3.10) (2026-02-20)


### Bug Fixes

* Bump llama index version for tests + fix tests ([#1992](https://github.com/TheTechOddBug/openinference/issues/1992)) ([a70bcd5](https://github.com/TheTechOddBug/openinference/commit/a70bcd5090568dcf48b56cc2feb081d33febf3de))
* Llama Index CI issues ([#2455](https://github.com/TheTechOddBug/openinference/issues/2455)) ([d8957a2](https://github.com/TheTechOddBug/openinference/commit/d8957a2d65c5a23b58e6f3decac76f1bc9e4d624))
* llama-index support vertex-ai token counts ([#1986](https://github.com/TheTechOddBug/openinference/issues/1986)) ([f75b573](https://github.com/TheTechOddBug/openinference/commit/f75b573fe09851a2708de8aa26fef388138256c3))
* **llama-index:** Fixing output messages attributes types ([#2291](https://github.com/TheTechOddBug/openinference/issues/2291)) ([45d9332](https://github.com/TheTechOddBug/openinference/commit/45d9332fb9571361ea397e82a6b3a1582c20f804))
* **llama-index:** handle BaseAgent import changes in v0.13.0+ ([#2023](https://github.com/TheTechOddBug/openinference/issues/2023)) ([62ce073](https://github.com/TheTechOddBug/openinference/commit/62ce073c98887851dd02dfd785b791e7e7ca9cb5))
* **llama-index:** tools ui fix ([#1802](https://github.com/TheTechOddBug/openinference/issues/1802)) ([c81bda4](https://github.com/TheTechOddBug/openinference/commit/c81bda4e490677913e72d48509112f544970d57c))
* non-ascii characters in input.value ([#2199](https://github.com/TheTechOddBug/openinference/issues/2199)) ([8bfdd0d](https://github.com/TheTechOddBug/openinference/commit/8bfdd0d65aae74649a1087ec6796193485e0a73b))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/TheTechOddBug/openinference/issues/2320)) ([c7eab4f](https://github.com/TheTechOddBug/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
</details>

<details><summary>python-openinference-instrumentation-dspy: 0.1.34</summary>

## [0.1.34](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-dspy-v0.1.33...python-openinference-instrumentation-dspy-v0.1.34) (2026-02-20)


### Features

* **dspy:** Instrument DSPy DummyLM ([#2067](https://github.com/TheTechOddBug/openinference/issues/2067)) ([0b0349d](https://github.com/TheTechOddBug/openinference/commit/0b0349d14f227ac6b51fdf461c4e614e8b80582a))


### Bug Fixes

* dspy ci test failures ([#2466](https://github.com/TheTechOddBug/openinference/issues/2466)) ([d8b3cbc](https://github.com/TheTechOddBug/openinference/commit/d8b3cbc0ac46bc069be371fa82ddd54611fafa2f))
* Dspy Uninstrumenting instrumented methods ([#2511](https://github.com/TheTechOddBug/openinference/issues/2511)) ([b9860ed](https://github.com/TheTechOddBug/openinference/commit/b9860ed0d4289a179805dcc196d94031414f6883))
* **dspy:** CI Failures For DSPy ([#2539](https://github.com/TheTechOddBug/openinference/issues/2539)) ([6a4e5d7](https://github.com/TheTechOddBug/openinference/commit/6a4e5d737923dd25e8b45ab67e4312c0c5c371e5))
* **dspy:** mask api keys passed as arguments ([#1990](https://github.com/TheTechOddBug/openinference/issues/1990)) ([98218a1](https://github.com/TheTechOddBug/openinference/commit/98218a1bf710f860a93eb941194e2abcc2eec63f))
* **dspy:** replace configure() with context() in async tests ([#2178](https://github.com/TheTechOddBug/openinference/issues/2178)) ([90c59e0](https://github.com/TheTechOddBug/openinference/commit/90c59e01c48a0d89a93172ed8e9d2436117b7cbc))
* **instrumentation-dspy:** pin urllib3&lt;2.0 for pytest-recording compatibility ([#2007](https://github.com/TheTechOddBug/openinference/issues/2007)) ([51f5040](https://github.com/TheTechOddBug/openinference/commit/51f5040af8bef8f7407dde7451ea1f2fb6ca7950))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-bedrock: 0.1.33</summary>

## [0.1.33](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-bedrock-v0.1.32...python-openinference-instrumentation-bedrock-v0.1.33) (2026-02-20)


### Features

* **bedrock-agents:** Added Support for bedrock invoke inline agent ([#2256](https://github.com/TheTechOddBug/openinference/issues/2256)) ([2d4e27e](https://github.com/TheTechOddBug/openinference/commit/2d4e27eb29496154ef26754de36eb10a4312f4e5))
* **bedrock:** Add instrumentation for guardrailTrace ([#2058](https://github.com/TheTechOddBug/openinference/issues/2058)) ([8ea1eef](https://github.com/TheTechOddBug/openinference/commit/8ea1eef5db0a334c5ca66c77f7217246156d7ef0))
* **bedrock:** Add Routing Classifier Trace event ([#2495](https://github.com/TheTechOddBug/openinference/issues/2495)) ([e878e1c](https://github.com/TheTechOddBug/openinference/commit/e878e1cdb7bf82601caf90ae8e7b66fbff23e02e))
* **bedrock:** added support for retrieve, retrieve and generate ([#1786](https://github.com/TheTechOddBug/openinference/issues/1786)) ([2652fa7](https://github.com/TheTechOddBug/openinference/commit/2652fa7372a02980b55425591f16b61626db297c))
* **bedrock:** Bedrock converse streaming support added ([#2172](https://github.com/TheTechOddBug/openinference/issues/2172)) ([5b9ba8f](https://github.com/TheTechOddBug/openinference/commit/5b9ba8f8739170cf1aa4e6ae359449382bcd9416))


### Bug Fixes

* **bedrock:** fix test compatibility with boto3-latest ([#2243](https://github.com/TheTechOddBug/openinference/issues/2243)) ([7cf5760](https://github.com/TheTechOddBug/openinference/commit/7cf576059859e370a3f83b60d0e2c9ff6d6971b7))
* **bedrock:** fixing invoke model api calls ([#1760](https://github.com/TheTechOddBug/openinference/issues/1760)) ([0ce91a5](https://github.com/TheTechOddBug/openinference/commit/0ce91a5da29c36160b16da7194c4c59dca24bed4))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-langchain: 0.1.60</summary>

## [0.1.60](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-langchain-v0.1.59...python-openinference-instrumentation-langchain-v0.1.60) (2026-02-20)


### Features

* add span attributes `llm.provider` and `llm.system` to langchain instrumentation ([#1791](https://github.com/TheTechOddBug/openinference/issues/1791)) ([545f52d](https://github.com/TheTechOddBug/openinference/commit/545f52d25ce803410d92ba7f18da8bf2a8d87087))
* Instrument sssistant tool calls made by LangGraph  ([#2012](https://github.com/TheTechOddBug/openinference/issues/2012)) ([f0e5852](https://github.com/TheTechOddBug/openinference/commit/f0e585258aca591dbb4e97cc1a7503b56971cebc))
* unwrap input output keys from io values ([#1993](https://github.com/TheTechOddBug/openinference/issues/1993)) ([534c727](https://github.com/TheTechOddBug/openinference/commit/534c72764a72cfd995ecf3d0f70ecaafc7cf359a))


### Bug Fixes

* anthropic token count ([#2428](https://github.com/TheTechOddBug/openinference/issues/2428)) ([698dc81](https://github.com/TheTechOddBug/openinference/commit/698dc81f731140efb128a84892f6c9579c879a10))
* Fix Langchain ([#2457](https://github.com/TheTechOddBug/openinference/issues/2457)) ([870bf16](https://github.com/TheTechOddBug/openinference/commit/870bf1678a2cfd0f2f77255c24b7899e2b6d3886))
* langchain auto instrumentor supports Python 3.14 ([#2292](https://github.com/TheTechOddBug/openinference/issues/2292)) ([53b438a](https://github.com/TheTechOddBug/openinference/commit/53b438acc181b1b482debbf9e9de263951d8c476))
* **langchain:** anthropic cache token count ([#2414](https://github.com/TheTechOddBug/openinference/issues/2414)) ([9f21f0f](https://github.com/TheTechOddBug/openinference/commit/9f21f0ffca32c9ba370c621166aa50a4743c6891))
* **Langchain:** Handle custom data in additional kwargs ([#1898](https://github.com/TheTechOddBug/openinference/issues/1898)) ([c7f71e1](https://github.com/TheTechOddBug/openinference/commit/c7f71e19a128ff6054cd66120bb00b79d70e51ef))
* **langchain:** Handle Non-String Dictionary Keys ([#2555](https://github.com/TheTechOddBug/openinference/issues/2555)) ([d0f8f8c](https://github.com/TheTechOddBug/openinference/commit/d0f8f8c2ed09913cdc45c86d3bd6dec78d10b700))
* **langchain:** handle None message id fields ([#2412](https://github.com/TheTechOddBug/openinference/issues/2412)) ([0df5bf0](https://github.com/TheTechOddBug/openinference/commit/0df5bf0cf7873d87e578ce7433c8642225b74597))
* **langchain:** import testing dependencies from changes brought by langchian v1.0.0 ([#2336](https://github.com/TheTechOddBug/openinference/issues/2336)) ([55c9a0d](https://github.com/TheTechOddBug/openinference/commit/55c9a0d3a6826f6a9c2fd76a108291a82e2f5b22))
* **Langchain:** map UsageMetadata object ([#2136](https://github.com/TheTechOddBug/openinference/issues/2136)) ([dab6cfd](https://github.com/TheTechOddBug/openinference/commit/dab6cfd72e6e537f0e8d0b5f78285f46182501fa))
* resolve Python daily cron failures (langchain, pipecat, openlit, agent-framework) ([#2724](https://github.com/TheTechOddBug/openinference/issues/2724)) ([87639c4](https://github.com/TheTechOddBug/openinference/commit/87639c48600a3e18ec16a3c75c185631916bd7f3))
* small typo in str() call ([#1822](https://github.com/TheTechOddBug/openinference/issues/1822)) ([4a7385b](https://github.com/TheTechOddBug/openinference/commit/4a7385b968330e420c67a9a9066fc0f95b4109c5))
* tool call for anthropic bedrock invoke model ([#1995](https://github.com/TheTechOddBug/openinference/issues/1995)) ([c26ffe5](https://github.com/TheTechOddBug/openinference/commit/c26ffe57e696221cd82c32e262b4cc8fd32fbe8a))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* use `llm_output` and `metadata` for model name ([#1819](https://github.com/TheTechOddBug/openinference/issues/1819)) ([8cb7439](https://github.com/TheTechOddBug/openinference/commit/8cb7439daf45910f918468651624519de1c1b8de))


### Documentation

* create gemini_tracing.py ([#1456](https://github.com/TheTechOddBug/openinference/issues/1456)) ([46e135f](https://github.com/TheTechOddBug/openinference/commit/46e135fdc394234e80510808fbd8b04746365b66))
</details>

<details><summary>python-openinference-instrumentation-guardrails: 0.1.11</summary>

## [0.1.11](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-guardrails-v0.1.10...python-openinference-instrumentation-guardrails-v0.1.11) (2026-02-20)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-crewai: 0.1.20</summary>

## [0.1.20](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-crewai-v0.1.19...python-openinference-instrumentation-crewai-v0.1.20) (2026-02-20)


### Features

* **crewai:** Add Kickoff ID Attribute in Root Level ([#2742](https://github.com/TheTechOddBug/openinference/issues/2742)) ([8df5581](https://github.com/TheTechOddBug/openinference/commit/8df558116cd3e596818640b69d5192497c16266c))
* **crewai:** add task name attribute to span ([#2740](https://github.com/TheTechOddBug/openinference/issues/2740)) ([66fb074](https://github.com/TheTechOddBug/openinference/commit/66fb074ff0dad21c6c4f8d5d0752f39ef87f13e8))
* **crewai:** capture graph.node.id and graph.node.parent_id semantics ([#1794](https://github.com/TheTechOddBug/openinference/issues/1794)) ([4645932](https://github.com/TheTechOddBug/openinference/commit/4645932b68f7ed5ab3ecd8818ddad9e1011c027e))
* **crewai:** Enable Tracing Support For CrewAI Flows ([#2286](https://github.com/TheTechOddBug/openinference/issues/2286)) ([4930cb1](https://github.com/TheTechOddBug/openinference/commit/4930cb11f86845b10b02ed2cab03c63880419915))
* **crewai:** Enable Tracing Support For CrewAI Metrics ([#2377](https://github.com/TheTechOddBug/openinference/issues/2377)) ([5e4b862](https://github.com/TheTechOddBug/openinference/commit/5e4b86223d73380c04561279b890bbf6d77f996f))
* **crewai:** enhance span naming to include crew, agent, and tool context ([#2202](https://github.com/TheTechOddBug/openinference/issues/2202)) ([af44991](https://github.com/TheTechOddBug/openinference/commit/af44991003f70fc21701b2f1ead8a19554cd37e2))


### Bug Fixes

* **crewai:** CI Failures For CrewAI ([#2359](https://github.com/TheTechOddBug/openinference/issues/2359)) ([0921129](https://github.com/TheTechOddBug/openinference/commit/092112969c663b2215bd8a036441b8341a15d239))
* **crewai:** CrewAI Flow Traces Not Generated With Async ([#2308](https://github.com/TheTechOddBug/openinference/issues/2308)) ([7e7f532](https://github.com/TheTechOddBug/openinference/commit/7e7f53283df61a0d78df01ab808bacdddd14620a))
* **crewai:** Not Getting Inputs For CrewAI Root Span ([#2193](https://github.com/TheTechOddBug/openinference/issues/2193)) ([9cf3b8f](https://github.com/TheTechOddBug/openinference/commit/9cf3b8fa0f432f6b6f783fc25a9d3d78f9164d4e))
* **crewai:** Not Getting Tool Spans From Latest CrewAI ([#2665](https://github.com/TheTechOddBug/openinference/issues/2665)) ([d80846f](https://github.com/TheTechOddBug/openinference/commit/d80846f897d8427b4bd58ddf510414838e42649c))
</details>

<details><summary>python-openinference-instrumentation-haystack: 0.1.30</summary>

## [0.1.30](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-haystack-v0.1.29...python-openinference-instrumentation-haystack-v0.1.30) (2026-02-20)


### Features

* **haysack-ai:** haystack async pipeline support ([#2300](https://github.com/TheTechOddBug/openinference/issues/2300)) ([abd8837](https://github.com/TheTechOddBug/openinference/commit/abd883711e519149142d214576e0ecf104e0a522))
* **haystack:** Added Components instrumentation ([#2383](https://github.com/TheTechOddBug/openinference/issues/2383)) ([f22d546](https://github.com/TheTechOddBug/openinference/commit/f22d54638a655078b6919e5e05b1678b613931e3))
* **haystack:** align embedding spans with OpenAI/LiteLLM patterns ([#2437](https://github.com/TheTechOddBug/openinference/issues/2437)) ([4e9685d](https://github.com/TheTechOddBug/openinference/commit/4e9685d375e43c40ccc494514cd71746d60d5d10))
* **haystack:** Populate LLM Provider & System Attributes ([#2743](https://github.com/TheTechOddBug/openinference/issues/2743)) ([5f676be](https://github.com/TheTechOddBug/openinference/commit/5f676beadbb4398ca926dea3ac76422b52bd7005))


### Bug Fixes

* **haystack:** support base64-encoded embeddings and list[Document] hints ([#2245](https://github.com/TheTechOddBug/openinference/issues/2245)) ([75e5a1f](https://github.com/TheTechOddBug/openinference/commit/75e5a1fbf245109fec99c6fde90dffe499380797))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-litellm: 0.1.30</summary>

## [0.1.30](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-litellm-v0.1.29...python-openinference-instrumentation-litellm-v0.1.30) (2026-02-20)


### Features

* **litellm:** add llm provider attributes ([#2094](https://github.com/TheTechOddBug/openinference/issues/2094)) ([86e681a](https://github.com/TheTechOddBug/openinference/commit/86e681aaf98116016848fc7d1b6c26a8c6607a25))
* **litellm:** Added Support for responses API in litellm instrumentor ([#2209](https://github.com/TheTechOddBug/openinference/issues/2209)) ([1abc662](https://github.com/TheTechOddBug/openinference/commit/1abc6624fc82381a2017f7871f1041391cea0eab))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/TheTechOddBug/openinference/issues/2238)) ([d03047d](https://github.com/TheTechOddBug/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **litellm:** track tool schemas from kwargs in litellm completion functions ([#1865](https://github.com/TheTechOddBug/openinference/issues/1865)) ([4df17c3](https://github.com/TheTechOddBug/openinference/commit/4df17c3562c1168db14af86fe5173b00e1ffadeb))


### Bug Fixes

* litellm async calls with stream reports token usage and span status ([#2480](https://github.com/TheTechOddBug/openinference/issues/2480)) ([fce93ef](https://github.com/TheTechOddBug/openinference/commit/fce93ef2243ffb1c4d539ecd2d9ac8e777912d3d))
* **litellm:** Fixing Invocation Params, Output Messages ([#1838](https://github.com/TheTechOddBug/openinference/issues/1838)) ([9f15912](https://github.com/TheTechOddBug/openinference/commit/9f15912bc87e697e1021db0b63e9d2c8b3d1e377))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-groq: 0.1.13</summary>

## [0.1.13](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-groq-v0.1.12...python-openinference-instrumentation-groq-v0.1.13) (2026-02-20)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-instructor: 0.1.14</summary>

## [0.1.14](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-instructor-v0.1.13...python-openinference-instrumentation-instructor-v0.1.14) (2026-02-20)


### Features

* **instructor:** Populate LLM Provider & System Attributes ([#2658](https://github.com/TheTechOddBug/openinference/issues/2658)) ([ae60838](https://github.com/TheTechOddBug/openinference/commit/ae608387a6ac75482587ba557202ee0f1c79734c))


### Bug Fixes

* **instructor:** Added compatibility with the latest instructor versi& ([#2287](https://github.com/TheTechOddBug/openinference/issues/2287)) ([5c5a02b](https://github.com/TheTechOddBug/openinference/commit/5c5a02b84ee07106c3f50c193fa803460baa3c32))
* **instructor:** JSON Serialization Error for max_retries in Span Attributes ([#2212](https://github.com/TheTechOddBug/openinference/issues/2212)) ([c6d1d40](https://github.com/TheTechOddBug/openinference/commit/c6d1d40e98a123bb1029d0b7e4120de45f81d100))
* **instructor:** make UserInfo fields optional for streaming partial responses ([#2295](https://github.com/TheTechOddBug/openinference/issues/2295)) ([5bb52cf](https://github.com/TheTechOddBug/openinference/commit/5bb52cfe25d0ec9693d562110c0af1097b7518b5))
* Refactor Helpers With More Test Coverage ([#2750](https://github.com/TheTechOddBug/openinference/issues/2750)) ([6cf0cd3](https://github.com/TheTechOddBug/openinference/commit/6cf0cd3b47dc58f92ea6a35dd5ccc9dfa588effa))
</details>

<details><summary>python-openinference-instrumentation-anthropic: 0.1.21</summary>

## [0.1.21](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-anthropic-v0.1.20...python-openinference-instrumentation-anthropic-v0.1.21) (2026-02-20)


### Features

* **anthropic:** Added support for anthropic sdk input images rendering  ([#2091](https://github.com/TheTechOddBug/openinference/issues/2091)) ([d2684b4](https://github.com/TheTechOddBug/openinference/commit/d2684b4b20e3b0199051c553580a8b27b673727f))


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-smolagents: 0.1.23</summary>

## [0.1.23](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-smolagents-v0.1.22...python-openinference-instrumentation-smolagents-v0.1.23) (2026-02-20)


### Features

* **smolagents:** Improve Display Of Handled Errors ([#1845](https://github.com/TheTechOddBug/openinference/issues/1845)) ([fb7eb1f](https://github.com/TheTechOddBug/openinference/commit/fb7eb1fa36adb7bb5ff001dce196c32ceb244a18))
* **smolagents:** Populate LLM Provider & System Attributes ([#2631](https://github.com/TheTechOddBug/openinference/issues/2631)) ([a9062f2](https://github.com/TheTechOddBug/openinference/commit/a9062f29ffbc9c980061d4fe5e25f09662e8b7ca))


### Bug Fixes

* Add handling for json dumping of non-serializable objects ([#2581](https://github.com/TheTechOddBug/openinference/issues/2581)) ([b6e44f8](https://github.com/TheTechOddBug/openinference/commit/b6e44f8734b623ae07339a5946a0e4e6d236e375))
* Refactor Helpers With More Test Coverage ([#2750](https://github.com/TheTechOddBug/openinference/issues/2750)) ([6cf0cd3](https://github.com/TheTechOddBug/openinference/commit/6cf0cd3b47dc58f92ea6a35dd5ccc9dfa588effa))
* **smolagents:** Getting Multiple Traces While Streaming Code Agent ([#1872](https://github.com/TheTechOddBug/openinference/issues/1872)) ([420ea79](https://github.com/TheTechOddBug/openinference/commit/420ea79a5fd2ce572cb7bdcb38b6585107cce465))
* **smolagents:** give agent run span as more descriptive span name ([#2454](https://github.com/TheTechOddBug/openinference/issues/2454)) ([6ffccce](https://github.com/TheTechOddBug/openinference/commit/6ffccce7e41892a9f2e1151c1337002e67b40119))
* **smolagents:** Not Getting Step Spans From Latest Smolagents ([#2171](https://github.com/TheTechOddBug/openinference/issues/2171)) ([14f0a19](https://github.com/TheTechOddBug/openinference/commit/14f0a1994a43476f77b1e906912d4a572d194700))
* **smolagents:** prevent duplicate llm spans ([#2118](https://github.com/TheTechOddBug/openinference/issues/2118)) ([f1a2946](https://github.com/TheTechOddBug/openinference/commit/f1a29460344d37e7e431d2bd76bc6f724bcbb931))
* **smolagents:** tool spans fix ([#2425](https://github.com/TheTechOddBug/openinference/issues/2425)) ([248d025](https://github.com/TheTechOddBug/openinference/commit/248d025c71cfc6b378b6128635c8e37a39afef20))
* **smolagents:** use new token_usage structure ([#2087](https://github.com/TheTechOddBug/openinference/issues/2087)) ([c691712](https://github.com/TheTechOddBug/openinference/commit/c6917124a236eb6deff1e1faf214075662ebfc58))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-autogen: 0.1.11</summary>

## [0.1.11](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-autogen-v0.1.10...python-openinference-instrumentation-autogen-v0.1.11) (2026-02-20)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-beeai: 0.1.16</summary>

## [0.1.16](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-beeai-v0.1.15...python-openinference-instrumentation-beeai-v0.1.16) (2026-02-20)


### Features

* BeeAI Framework Updates ([#2060](https://github.com/TheTechOddBug/openinference/issues/2060)) ([720d1fe](https://github.com/TheTechOddBug/openinference/commit/720d1fe2db55fa95fa9721438b441c4f7924c726))
* **beeai:** Added tools support in beeai instrumentation ([#2543](https://github.com/TheTechOddBug/openinference/issues/2543)) ([29e415d](https://github.com/TheTechOddBug/openinference/commit/29e415da3df38a2e106959bdec98916357691c4f))
* **beeai:** align embedding spans with OpenAI/LiteLLM patterns ([#2438](https://github.com/TheTechOddBug/openinference/issues/2438)) ([9cb15d4](https://github.com/TheTechOddBug/openinference/commit/9cb15d433556a0e7a2e8631e14f3f97b5009a05f))
* update BeeAI data serialization ([#2108](https://github.com/TheTechOddBug/openinference/issues/2108)) ([0994ec5](https://github.com/TheTechOddBug/openinference/commit/0994ec58ffbb905da975b5e0be5ea9b512ca528b))
* update beeai-framework ([#2227](https://github.com/TheTechOddBug/openinference/issues/2227)) ([8f8204d](https://github.com/TheTechOddBug/openinference/commit/8f8204dfb5e2de4ad172f4af2cba056435bf5762))
* update beeai-framework integration ([#1829](https://github.com/TheTechOddBug/openinference/issues/1829)) ([c788ec3](https://github.com/TheTechOddBug/openinference/commit/c788ec3b8f1783fba1bb3d57022523d5de684b0a))


### Bug Fixes

* **beeaI:** dedupe traces/spans ([#2148](https://github.com/TheTechOddBug/openinference/issues/2148)) ([c528758](https://github.com/TheTechOddBug/openinference/commit/c5287584878089c4ea891b6768c5f2e4d86cbdb9))
* **beeai:** update for RequirementAgent move from experimental to stable ([#2255](https://github.com/TheTechOddBug/openinference/issues/2255)) ([f511485](https://github.com/TheTechOddBug/openinference/commit/f51148592ac904b488fbe5c0d8a0815a09e34ad3))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-portkey: 0.1.8</summary>

## [0.1.8](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-portkey-v0.1.7...python-openinference-instrumentation-portkey-v0.1.8) (2026-02-20)


### Features

* **portkey:** Support instrumentation of `portkey_ai.AsyncPortkey` ([#2407](https://github.com/TheTechOddBug/openinference/issues/2407)) ([118ef32](https://github.com/TheTechOddBug/openinference/commit/118ef329a797c59e1e91ce00a3a13fd165c8fded))


### Bug Fixes

* **portkey:** CI Failures For Portkey ([#2368](https://github.com/TheTechOddBug/openinference/issues/2368)) ([3654315](https://github.com/TheTechOddBug/openinference/commit/365431588857ae5f15385f9dfc2f681e386b9845))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/TheTechOddBug/openinference/issues/2320)) ([c7eab4f](https://github.com/TheTechOddBug/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
</details>

<details><summary>python-openinference-instrumentation-mcp: 1.3.4</summary>

## [1.3.4](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-mcp-v1.3.3...python-openinference-instrumentation-mcp-v1.3.4) (2026-02-20)


### Bug Fixes

* **mcp:** handle ValidationError in stdio stream instrumentation ([#2170](https://github.com/TheTechOddBug/openinference/issues/2170)) ([48aa236](https://github.com/TheTechOddBug/openinference/commit/48aa2362a97a7efb029bd1f1e339297e6c6feec0))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/TheTechOddBug/openinference/issues/2320)) ([c7eab4f](https://github.com/TheTechOddBug/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
</details>

<details><summary>python-openinference-instrumentation-google-genai: 0.1.11</summary>

## [0.1.11](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-google-genai-v0.1.10...python-openinference-instrumentation-google-genai-v0.1.11) (2026-02-20)


### Features

* Google Gen AI Tool Code Support ([#1763](https://github.com/TheTechOddBug/openinference/issues/1763)) ([ec5cc3f](https://github.com/TheTechOddBug/openinference/commit/ec5cc3f535cfb546f08506d18b93c373b494c7c2))
* **google-genai:** interactions api integration ([#2628](https://github.com/TheTechOddBug/openinference/issues/2628)) ([23a9702](https://github.com/TheTechOddBug/openinference/commit/23a9702bbd9fcf0bd9a3013bcac59ecf375d2c8f))


### Bug Fixes

* fix config_json serialization for GoogleGenAIInstrumentor ([#1855](https://github.com/TheTechOddBug/openinference/issues/1855)) ([1702a1d](https://github.com/TheTechOddBug/openinference/commit/1702a1d755d8ebc64fb3fa17e36579a6935d9dbd))
* **google-genai:** fix wrong tool attribute when setting llm input_message attribute ([#2260](https://github.com/TheTechOddBug/openinference/issues/2260)) ([8ee0569](https://github.com/TheTechOddBug/openinference/commit/8ee0569ae3e7bbf8c66f8bca2a34727d31cd007d))
* **google-genai:** including tool_use_prompt_token_count into prompt token count ([#2597](https://github.com/TheTechOddBug/openinference/issues/2597)) ([b067ecb](https://github.com/TheTechOddBug/openinference/commit/b067ecb133dd7dcf7eccf15d20450817a71953dd))
* **google-genai:** Set input message attributes for function call and function response parts ([#2252](https://github.com/TheTechOddBug/openinference/issues/2252)) ([be4b9c1](https://github.com/TheTechOddBug/openinference/commit/be4b9c150f6a33a1ee394d19f7c8e7c7886fe307))
* include reasoning and audio token count for genai and adk instrumentors ([#1812](https://github.com/TheTechOddBug/openinference/issues/1812)) ([921ff07](https://github.com/TheTechOddBug/openinference/commit/921ff073e28ac2755b651dcdfac9ab3dbd673e70))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-autogen-agentchat: 0.1.7</summary>

## [0.1.7](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-autogen-agentchat-v0.1.6...python-openinference-instrumentation-autogen-agentchat-v0.1.7) (2026-02-20)


### Features

* **autogen-agentchat:** add tool call semantic convention attributes ([#2104](https://github.com/TheTechOddBug/openinference/issues/2104)) ([fe0780d](https://github.com/TheTechOddBug/openinference/commit/fe0780d243e9ecf89e6548e5793c7265dede1b86))
* **autogen-agentchat:** capture graph.node.id and graph.node.parent_id semantics ([#1867](https://github.com/TheTechOddBug/openinference/issues/1867)) ([9f8ca03](https://github.com/TheTechOddBug/openinference/commit/9f8ca0373856e94305e531ef1e325525b5958ff9))
* **autogen-agentchat:** instrumenting AssistantAgent, BaseOpenAIChatCompletionClient, and BaseGroupChat ([#1790](https://github.com/TheTechOddBug/openinference/issues/1790)) ([3a53ede](https://github.com/TheTechOddBug/openinference/commit/3a53ede8716e1a2d862ec653740b93881ebb1106))


### Bug Fixes

* **autogen-agentchat:** filter out invalid kwargs before binding calls and record new vcrs for tests for autogen version 0.6.x ([#1871](https://github.com/TheTechOddBug/openinference/issues/1871)) ([9c4ada0](https://github.com/TheTechOddBug/openinference/commit/9c4ada0847be85fff074ef493ad2f138f80369d2))
* autogent-agentchat modelname fix ([#2436](https://github.com/TheTechOddBug/openinference/issues/2436)) ([1547025](https://github.com/TheTechOddBug/openinference/commit/1547025474eef190d1ae85b49faa8f9c3329db08))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-pydantic-ai: 0.1.13</summary>

## [0.1.13](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-pydantic-ai-v0.1.12...python-openinference-instrumentation-pydantic-ai-v0.1.13) (2026-02-20)


### Features

* **pydantic_ai:** Populate LLM Provider & System Attributes ([#2635](https://github.com/TheTechOddBug/openinference/issues/2635)) ([3c7774f](https://github.com/TheTechOddBug/openinference/commit/3c7774fc8af8bec17ca1b9700ee3f0c5baad2da0))
* **pydentic_ai:** tools & multiple input/output messages support ([#2508](https://github.com/TheTechOddBug/openinference/issues/2508)) ([16c6ef2](https://github.com/TheTechOddBug/openinference/commit/16c6ef20d714f37e109df2873718f4777eaebfc6))
* update pydantic-ai to v2 tracing format ([#2186](https://github.com/TheTechOddBug/openinference/issues/2186)) ([5eecce5](https://github.com/TheTechOddBug/openinference/commit/5eecce5c648d710d3ad9397e23773096e5903352))


### Bug Fixes

* **pydantic_ai:** Update Invalid Span Attribute For Tool Results ([#2729](https://github.com/TheTechOddBug/openinference/issues/2729)) ([c4c5056](https://github.com/TheTechOddBug/openinference/commit/c4c50566ad1e438293d8dae95d390aad3951beb8))
* pydantic-ai add tool call result ([#2305](https://github.com/TheTechOddBug/openinference/issues/2305)) ([ede428c](https://github.com/TheTechOddBug/openinference/commit/ede428cc5653b1c8d89c6ba68753a1a57fb2bacd))
* pydantic-ai fix span filtering ([#2016](https://github.com/TheTechOddBug/openinference/issues/2016)) ([c139f36](https://github.com/TheTechOddBug/openinference/commit/c139f3677233fb7c76b0b2bff5b4a2dafe1921dc))
* pydantic-ai properly instrument tools and instructions ([#2250](https://github.com/TheTechOddBug/openinference/issues/2250)) ([6458835](https://github.com/TheTechOddBug/openinference/commit/64588357d31137dafcd855c9c610ce241dcd0519))
* pydantic-ai use final user message as input value ([#2237](https://github.com/TheTechOddBug/openinference/issues/2237)) ([208232d](https://github.com/TheTechOddBug/openinference/commit/208232dfd6d47e8123beea41c47c8fc556012325))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-google-adk: 0.1.10</summary>

## [0.1.10](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-google-adk-v0.1.9...python-openinference-instrumentation-google-adk-v0.1.10) (2026-02-20)


### Features

* google adk artifacts ([#2570](https://github.com/TheTechOddBug/openinference/issues/2570)) ([45f7027](https://github.com/TheTechOddBug/openinference/commit/45f70276a829bd2e41217e67daf9ae84b30b545e))
* **google-adk:** Add agent.name attribute to agent run spans and add multi-agent test ([#2510](https://github.com/TheTechOddBug/openinference/issues/2510)) ([d08f500](https://github.com/TheTechOddBug/openinference/commit/d08f5002a13e11cee6e230dbe56a6667a5101fca))


### Bug Fixes

* Google adk ci failures ([#2484](https://github.com/TheTechOddBug/openinference/issues/2484)) ([2d9864c](https://github.com/TheTechOddBug/openinference/commit/2d9864ce6cd41419dbf02e009e19d1c3fa626e46))
* **google-adk:** Capture all tool results when LLM makes multiple parallel tool calls ([#2483](https://github.com/TheTechOddBug/openinference/issues/2483)) ([5fc74e4](https://github.com/TheTechOddBug/openinference/commit/5fc74e4fcb8f9e322b067233aaa8605e672d53b4))
* **google-adk:** fix test compatibility with v1.13.0 ([#2176](https://github.com/TheTechOddBug/openinference/issues/2176)) ([dbe0668](https://github.com/TheTechOddBug/openinference/commit/dbe066844397be079e90900ab3eff9a920dbf436))
* **google-adk:** remove dependency on private telemetry API ([#2244](https://github.com/TheTechOddBug/openinference/issues/2244)) ([e07939d](https://github.com/TheTechOddBug/openinference/commit/e07939d2ae530212e81004ef466d01e34f798b2d))
* include reasoning and audio token count for genai and adk instrumentors ([#1812](https://github.com/TheTechOddBug/openinference/issues/1812)) ([921ff07](https://github.com/TheTechOddBug/openinference/commit/921ff073e28ac2755b651dcdfac9ab3dbd673e70))
* pydantic model serialization for input value and image bytes for google-adk ([#2031](https://github.com/TheTechOddBug/openinference/issues/2031)) ([46ef152](https://github.com/TheTechOddBug/openinference/commit/46ef1522f73cf98f8c2b318b7afc7444160033b3))
* serialization of response schema in invocation parameters for google-adk ([#2033](https://github.com/TheTechOddBug/openinference/issues/2033)) ([586689f](https://github.com/TheTechOddBug/openinference/commit/586689f4ec6a37a6f3961740ebff4734f92ec3e5))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-openlit: 0.1.5</summary>

## [0.1.5](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-openlit-v0.1.4...python-openinference-instrumentation-openlit-v0.1.5) (2026-02-20)


### Features

* Openlit span processor ([#2021](https://github.com/TheTechOddBug/openinference/issues/2021)) ([99c4c99](https://github.com/TheTechOddBug/openinference/commit/99c4c994b42486192bf07699ea6b75c3bd29efa1))
* Openlit span processor ([#2120](https://github.com/TheTechOddBug/openinference/issues/2120)) ([5280702](https://github.com/TheTechOddBug/openinference/commit/5280702ac7df30575eeb4bac416411f43c43ad8b))
* Openlit span processor ([#2127](https://github.com/TheTechOddBug/openinference/issues/2127)) ([a039137](https://github.com/TheTechOddBug/openinference/commit/a039137c99f4162963fab37359df04763310e001))
* **openlit:** implement span processor ([#2149](https://github.com/TheTechOddBug/openinference/issues/2149)) ([51689ae](https://github.com/TheTechOddBug/openinference/commit/51689aea3c41b513b22dcf3513389e91ec4c8f1e))
* **openlit:** openlit span processor ([#2151](https://github.com/TheTechOddBug/openinference/issues/2151)) ([013102e](https://github.com/TheTechOddBug/openinference/commit/013102e586ab0f8e441c6caec02c5b4c48bd5643))
* **openlit:** Populate LLM Provider & System Attributes ([#2714](https://github.com/TheTechOddBug/openinference/issues/2714)) ([e01383b](https://github.com/TheTechOddBug/openinference/commit/e01383b5a63331bcd53e61265aa366224480a4aa))


### Bug Fixes

* fixing comments/file strings in openinference-instrumentation-openlit ([#2159](https://github.com/TheTechOddBug/openinference/issues/2159)) ([7a0a9d1](https://github.com/TheTechOddBug/openinference/commit/7a0a9d146aa2ce7f060e996c05b15b9dbbedb2fc))
* resolve Python daily cron failures (langchain, pipecat, openlit, agent-framework) ([#2724](https://github.com/TheTechOddBug/openinference/issues/2724)) ([87639c4](https://github.com/TheTechOddBug/openinference/commit/87639c48600a3e18ec16a3c75c185631916bd7f3))
</details>

<details><summary>python-openinference-instrumentation-openllmetry: 0.1.5</summary>

## [0.1.5](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-openllmetry-v0.1.4...python-openinference-instrumentation-openllmetry-v0.1.5) (2026-02-20)


### Features

* openinference-instrumentation-openllmetry (openllmetry converter) ([#1789](https://github.com/TheTechOddBug/openinference/issues/1789)) ([55fb98e](https://github.com/TheTechOddBug/openinference/commit/55fb98e8f23dd1d485a760e04496e0629bce6de0))
* Openlit span processor ([#2021](https://github.com/TheTechOddBug/openinference/issues/2021)) ([99c4c99](https://github.com/TheTechOddBug/openinference/commit/99c4c994b42486192bf07699ea6b75c3bd29efa1))
* **openllmetry:** Populate LLM Provider & System Attributes ([#2642](https://github.com/TheTechOddBug/openinference/issues/2642)) ([0bbfd89](https://github.com/TheTechOddBug/openinference/commit/0bbfd8908f685041d8f0b357b9508a81f0a4203c))


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/TheTechOddBug/openinference/issues/2294)) ([48b7a51](https://github.com/TheTechOddBug/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-pipecat: 0.1.4</summary>

## [0.1.4](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-pipecat-v0.1.3...python-openinference-instrumentation-pipecat-v0.1.4) (2026-02-20)


### Features

* **pipecat:** add auto instrumentor for pipecat ([#2441](https://github.com/TheTechOddBug/openinference/issues/2441)) ([956a3d8](https://github.com/TheTechOddBug/openinference/commit/956a3d8e3ee6f6fbe4efdebd81abe23732c10951))


### Bug Fixes

* **pipecat:** adding updates for tool calls ([#2661](https://github.com/TheTechOddBug/openinference/issues/2661)) ([06b3c5c](https://github.com/TheTechOddBug/openinference/commit/06b3c5cb85ceb06abbd8fd32d27d2fb01d036cc8))
* **pipecat:** pipecat instrumentor improvement of TTS output ([#2586](https://github.com/TheTechOddBug/openinference/issues/2586)) ([3c1a1ae](https://github.com/TheTechOddBug/openinference/commit/3c1a1ae5e39a33085f0adae6209634062277cb06))
* resolve Python daily cron failures (langchain, pipecat, openlit, agent-framework) ([#2724](https://github.com/TheTechOddBug/openinference/issues/2724)) ([87639c4](https://github.com/TheTechOddBug/openinference/commit/87639c48600a3e18ec16a3c75c185631916bd7f3))
* update for pipecat release ([#2582](https://github.com/TheTechOddBug/openinference/issues/2582)) ([02e13dc](https://github.com/TheTechOddBug/openinference/commit/02e13dc9ff680877bbcf8cc78a0c4653afc72d7d))
</details>

<details><summary>python-openinference-instrumentation-strands-agents: 0.1.2</summary>

## [0.1.2](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-strands-agents-v0.1.1...python-openinference-instrumentation-strands-agents-v0.1.2) (2026-02-20)


### Features

* rename strands to strands-agents instrumentor and add it to release-please config ([#2652](https://github.com/TheTechOddBug/openinference/issues/2652)) ([1946b66](https://github.com/TheTechOddBug/openinference/commit/1946b665d05dc504ae688eb8a7db3aed0ed76d53))
</details>

<details><summary>python-openinference-instrumentation-agent-framework: 0.1.3</summary>

## [0.1.3](https://github.com/TheTechOddBug/openinference/compare/python-openinference-instrumentation-agent-framework-v0.1.2...python-openinference-instrumentation-agent-framework-v0.1.3) (2026-02-20)


### Features

* add OpenInference instrumentation for Microsoft Agent Framework ([#2580](https://github.com/TheTechOddBug/openinference/issues/2580)) ([72cd5e6](https://github.com/TheTechOddBug/openinference/commit/72cd5e62077ca95d220094b27433f974ff6d8fb2))


### Bug Fixes

* resolve Python daily cron failures (langchain, pipecat, openlit, agent-framework) ([#2724](https://github.com/TheTechOddBug/openinference/issues/2724)) ([87639c4](https://github.com/TheTechOddBug/openinference/commit/87639c48600a3e18ec16a3c75c185631916bd7f3))
</details>

<details><summary>java-openinference-semantic-conventions: 0.1.10</summary>

## [0.1.10](https://github.com/TheTechOddBug/openinference/compare/java-openinference-semantic-conventions-v0.1.9...java-openinference-semantic-conventions-v0.1.10) (2026-02-20)


### Features

* Java release only, please ([#1881](https://github.com/TheTechOddBug/openinference/issues/1881)) ([0c75997](https://github.com/TheTechOddBug/openinference/commit/0c759977688c05a813a5121255f9da063aa9b4b0))
* **java:** add tool calling instrumentation, prepare dependabot PR ([#1901](https://github.com/TheTechOddBug/openinference/issues/1901)) ([33d3ded](https://github.com/TheTechOddBug/openinference/commit/33d3ded20fbd3097b4ee567c77d540526c480555))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/TheTechOddBug/openinference/issues/1817)) ([9ffb378](https://github.com/TheTechOddBug/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/TheTechOddBug/openinference/issues/2050)) ([3afeed2](https://github.com/TheTechOddBug/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/TheTechOddBug/openinference/issues/2036)) ([b260225](https://github.com/TheTechOddBug/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/TheTechOddBug/openinference/issues/2044)) ([2084e8e](https://github.com/TheTechOddBug/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/TheTechOddBug/openinference/issues/1887)) ([ffda77a](https://github.com/TheTechOddBug/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/TheTechOddBug/openinference/issues/1875)) ([8bd49ee](https://github.com/TheTechOddBug/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
* exclude java from python release path, read version from gradle.& ([#1877](https://github.com/TheTechOddBug/openinference/issues/1877)) ([f2a14bc](https://github.com/TheTechOddBug/openinference/commit/f2a14bc212491a01417eb08975be6ee0f9f99355))
* snapshot publish ([#1883](https://github.com/TheTechOddBug/openinference/issues/1883)) ([1c2532e](https://github.com/TheTechOddBug/openinference/commit/1c2532ecc2abb82c8bbdd87091a565dafd705756))
* SpringAI linking with correct dependencies ([#2098](https://github.com/TheTechOddBug/openinference/issues/2098)) ([8d944f8](https://github.com/TheTechOddBug/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
* typo on release ([#1884](https://github.com/TheTechOddBug/openinference/issues/1884)) ([5c2718e](https://github.com/TheTechOddBug/openinference/commit/5c2718e4dabff57be14f897ad8da23b03d208eab))
</details>

<details><summary>java-openinference-instrumentation: 0.1.8</summary>

## [0.1.8](https://github.com/TheTechOddBug/openinference/compare/java-openinference-instrumentation-v0.1.7...java-openinference-instrumentation-v0.1.8) (2026-02-20)


### Features

* add dependabot github action ([#1904](https://github.com/TheTechOddBug/openinference/issues/1904)) ([1283dfc](https://github.com/TheTechOddBug/openinference/commit/1283dfc3fcc9f728780f8c6a1ab865aa1f647a63))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/TheTechOddBug/openinference/issues/1817)) ([9ffb378](https://github.com/TheTechOddBug/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/TheTechOddBug/openinference/issues/2050)) ([3afeed2](https://github.com/TheTechOddBug/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/TheTechOddBug/openinference/issues/2036)) ([b260225](https://github.com/TheTechOddBug/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/TheTechOddBug/openinference/issues/2044)) ([2084e8e](https://github.com/TheTechOddBug/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/TheTechOddBug/openinference/issues/1887)) ([ffda77a](https://github.com/TheTechOddBug/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/TheTechOddBug/openinference/issues/1875)) ([8bd49ee](https://github.com/TheTechOddBug/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
* SpringAI linking with correct dependencies ([#2098](https://github.com/TheTechOddBug/openinference/issues/2098)) ([8d944f8](https://github.com/TheTechOddBug/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
</details>

<details><summary>java-openinference-instrumentation-langchain4j: 0.1.6</summary>

## [0.1.6](https://github.com/TheTechOddBug/openinference/compare/java-openinference-instrumentation-langchain4j-v0.1.5...java-openinference-instrumentation-langchain4j-v0.1.6) (2026-02-20)


### Features

* **java:** add tool calling instrumentation, prepare dependabot PR ([#1901](https://github.com/TheTechOddBug/openinference/issues/1901)) ([33d3ded](https://github.com/TheTechOddBug/openinference/commit/33d3ded20fbd3097b4ee567c77d540526c480555))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/TheTechOddBug/openinference/issues/1817)) ([9ffb378](https://github.com/TheTechOddBug/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/TheTechOddBug/openinference/issues/2050)) ([3afeed2](https://github.com/TheTechOddBug/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/TheTechOddBug/openinference/issues/2036)) ([b260225](https://github.com/TheTechOddBug/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/TheTechOddBug/openinference/issues/2044)) ([2084e8e](https://github.com/TheTechOddBug/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/TheTechOddBug/openinference/issues/1887)) ([ffda77a](https://github.com/TheTechOddBug/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/TheTechOddBug/openinference/issues/1875)) ([8bd49ee](https://github.com/TheTechOddBug/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
</details>

<details><summary>java-openinference-instrumentation-springAI: 0.1.8</summary>

## [0.1.8](https://github.com/TheTechOddBug/openinference/compare/java-openinference-instrumentation-springAI-v0.1.7...java-openinference-instrumentation-springAI-v0.1.8) (2026-02-20)


### Features

* new experimental release ([#2050](https://github.com/TheTechOddBug/openinference/issues/2050)) ([3afeed2](https://github.com/TheTechOddBug/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/TheTechOddBug/openinference/issues/2036)) ([b260225](https://github.com/TheTechOddBug/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/TheTechOddBug/openinference/issues/2044)) ([2084e8e](https://github.com/TheTechOddBug/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))


### Bug Fixes

* jreleaser dependency release, all packages need their version ([#2075](https://github.com/TheTechOddBug/openinference/issues/2075)) ([5a2de93](https://github.com/TheTechOddBug/openinference/commit/5a2de939136b2d151a831e8911a62a0c3f7b7717))
* SpringAI linking with correct dependencies ([#2098](https://github.com/TheTechOddBug/openinference/issues/2098)) ([8d944f8](https://github.com/TheTechOddBug/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
* SpringAI multiple output messages ([#2106](https://github.com/TheTechOddBug/openinference/issues/2106)) ([3c5fd97](https://github.com/TheTechOddBug/openinference/commit/3c5fd97ed045a36dd95d4689a8b5315b95ee6366))
* trigger springAI release ([#2061](https://github.com/TheTechOddBug/openinference/issues/2061)) ([e97f324](https://github.com/TheTechOddBug/openinference/commit/e97f324ca8a12d788148edd9a031fabfe7055e55))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).