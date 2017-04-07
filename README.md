# api documentation for  [pos (v0.4.2)](https://github.com/dariusk/pos-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-pos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pos)
#### fasttag part of speech tagger implementation

[![NPM](https://nodei.co/npm/pos.png?downloads=true)](https://www.npmjs.com/package/pos)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pos/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pos_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Percy Wegmann"
    },
    "bugs": {
        "url": "https://github.com/dariusk/pos-js/issues"
    },
    "contributors": [
        {
            "name": "Darius Kazemi",
            "email": "darius.kazemi@gmail.com",
            "url": "http://tinysubversions.com"
        }
    ],
    "dependencies": {},
    "description": "fasttag part of speech tagger implementation",
    "devDependencies": {
        "mocha": "~2.1.0",
        "should": "~5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "20e9c77fbeedcc356823cea63c7585cace93be2a",
        "tarball": "https://registry.npmjs.org/pos/-/pos-0.4.2.tgz"
    },
    "engines": {
        "node": ">=0"
    },
    "gitHead": "0abed44a6f8a5997e77daaa7d479a359b4611180",
    "homepage": "https://github.com/dariusk/pos-js",
    "keywords": [
        "nlp",
        "pos",
        "part of speech",
        "jspos",
        "fasttag"
    ],
    "licenses": [
        {
            "type": "LGPL",
            "url": "http://www.gnu.org/licenses/lgpl.html"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "gerad",
            "email": "gerads@gmail.com"
        },
        {
            "name": "dariusk",
            "email": "darius.kazemi@gmail.com"
        }
    ],
    "name": "pos",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/dariusk/pos-js.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pos](#apidoc.module.pos)
1.  [function <span class="apidocSignatureSpan">pos.</span>BrillTransformationRules ()](#apidoc.element.pos.BrillTransformationRules)
1.  [function <span class="apidocSignatureSpan">pos.</span>Lexer ()](#apidoc.element.pos.Lexer)
1.  [function <span class="apidocSignatureSpan">pos.</span>Tagger ()](#apidoc.element.pos.Tagger)
1.  object <span class="apidocSignatureSpan">pos.</span>BrillTransformationRules.prototype
1.  object <span class="apidocSignatureSpan">pos.</span>Lexer.prototype
1.  object <span class="apidocSignatureSpan">pos.</span>Tagger.prototype

#### [module pos.BrillTransformationRules](#apidoc.module.pos.BrillTransformationRules)
1.  [function <span class="apidocSignatureSpan">pos.</span>BrillTransformationRules ()](#apidoc.element.pos.BrillTransformationRules.BrillTransformationRules)

#### [module pos.BrillTransformationRules.prototype](#apidoc.module.pos.BrillTransformationRules.prototype)
1.  [function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>appendRule (rule)](#apidoc.element.pos.BrillTransformationRules.prototype.appendRule)
1.  [function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>getRule (index)](#apidoc.element.pos.BrillTransformationRules.prototype.getRule)
1.  [function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>getRules ()](#apidoc.element.pos.BrillTransformationRules.prototype.getRules)
1.  [function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>setRule (index, rule)](#apidoc.element.pos.BrillTransformationRules.prototype.setRule)
1.  [function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>setRules (newRules)](#apidoc.element.pos.BrillTransformationRules.prototype.setRules)

#### [module pos.Lexer](#apidoc.module.pos.Lexer)
1.  [function <span class="apidocSignatureSpan">pos.</span>Lexer ()](#apidoc.element.pos.Lexer.Lexer)

#### [module pos.Lexer.prototype](#apidoc.module.pos.Lexer.prototype)
1.  [function <span class="apidocSignatureSpan">pos.Lexer.prototype.</span>lex (string)](#apidoc.element.pos.Lexer.prototype.lex)

#### [module pos.Tagger](#apidoc.module.pos.Tagger)
1.  [function <span class="apidocSignatureSpan">pos.</span>Tagger ()](#apidoc.element.pos.Tagger.Tagger)

#### [module pos.Tagger.prototype](#apidoc.module.pos.Tagger.prototype)
1.  [function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>extendLexicon (lexicon)](#apidoc.element.pos.Tagger.prototype.extendLexicon)
1.  [function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>prettyPrint (taggedWords)](#apidoc.element.pos.Tagger.prototype.prettyPrint)
1.  [function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>tag (words)](#apidoc.element.pos.Tagger.prototype.tag)
1.  [function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>wordInLexicon (word)](#apidoc.element.pos.Tagger.prototype.wordInLexicon)



# <a name="apidoc.module.pos"></a>[module pos](#apidoc.module.pos)

#### <a name="apidoc.element.pos.BrillTransformationRules"></a>[function <span class="apidocSignatureSpan">pos.</span>BrillTransformationRules ()](#apidoc.element.pos.BrillTransformationRules)
- description and source-code
```javascript
function BrillTransformationRules() {
  this.rules = [rule1, rule2, rule3, rule4, rule5, rule6, rule7, rule8];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.Lexer"></a>[function <span class="apidocSignatureSpan">pos.</span>Lexer ()](#apidoc.element.pos.Lexer)
- description and source-code
```javascript
function Lexer(){
  // URLS can contain IDS, so first urls, then ids
  // then split by then numbers, then whitespace, then email and finally punctuation
  // this.regexs = [re.urls, re.ids, re.number, re.space, re.email, re.punctuation];
  this.regexs = [
    re.urls, re.ids, re.time, re.number, re.space, re.email, re.punctuation
  ];
}
```
- example usage
```shell
...

'$ npm install pos'

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
var taggedWord = taggedWords[i];
var word = taggedWord[0];
var tag = taggedWord[1];
console.log(word + " /" + tag);
...
```

#### <a name="apidoc.element.pos.Tagger"></a>[function <span class="apidocSignatureSpan">pos.</span>Tagger ()](#apidoc.element.pos.Tagger)
- description and source-code
```javascript
function POSTagger(){
    this.lexicon = require('./lexicon');
}
```
- example usage
```shell
...
'$ npm install pos'

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
    var taggedWord = taggedWords[i];
    var word = taggedWord[0];
    var tag = taggedWord[1];
    console.log(word + " /" + tag);
}
...
```



# <a name="apidoc.module.pos.BrillTransformationRules"></a>[module pos.BrillTransformationRules](#apidoc.module.pos.BrillTransformationRules)

#### <a name="apidoc.element.pos.BrillTransformationRules.BrillTransformationRules"></a>[function <span class="apidocSignatureSpan">pos.</span>BrillTransformationRules ()](#apidoc.element.pos.BrillTransformationRules.BrillTransformationRules)
- description and source-code
```javascript
function BrillTransformationRules() {
  this.rules = [rule1, rule2, rule3, rule4, rule5, rule6, rule7, rule8];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pos.BrillTransformationRules.prototype"></a>[module pos.BrillTransformationRules.prototype](#apidoc.module.pos.BrillTransformationRules.prototype)

#### <a name="apidoc.element.pos.BrillTransformationRules.prototype.appendRule"></a>[function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>appendRule (rule)](#apidoc.element.pos.BrillTransformationRules.prototype.appendRule)
- description and source-code
```javascript
appendRule = function (rule) {
  this.rules[this.rules.length] = rule;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.BrillTransformationRules.prototype.getRule"></a>[function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>getRule (index)](#apidoc.element.pos.BrillTransformationRules.prototype.getRule)
- description and source-code
```javascript
getRule = function (index) {
  return(this.rules[index]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.BrillTransformationRules.prototype.getRules"></a>[function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>getRules ()](#apidoc.element.pos.BrillTransformationRules.prototype.getRules)
- description and source-code
```javascript
getRules = function () {
  return(this.rules);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.BrillTransformationRules.prototype.setRule"></a>[function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>setRule (index, rule)](#apidoc.element.pos.BrillTransformationRules.prototype.setRule)
- description and source-code
```javascript
setRule = function (index, rule) {
  this.rules[index] = rule;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.BrillTransformationRules.prototype.setRules"></a>[function <span class="apidocSignatureSpan">pos.BrillTransformationRules.prototype.</span>setRules (newRules)](#apidoc.element.pos.BrillTransformationRules.prototype.setRules)
- description and source-code
```javascript
setRules = function (newRules) {
  this.rules = newRules;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pos.Lexer"></a>[module pos.Lexer](#apidoc.module.pos.Lexer)

#### <a name="apidoc.element.pos.Lexer.Lexer"></a>[function <span class="apidocSignatureSpan">pos.</span>Lexer ()](#apidoc.element.pos.Lexer.Lexer)
- description and source-code
```javascript
function Lexer(){
  // URLS can contain IDS, so first urls, then ids
  // then split by then numbers, then whitespace, then email and finally punctuation
  // this.regexs = [re.urls, re.ids, re.number, re.space, re.email, re.punctuation];
  this.regexs = [
    re.urls, re.ids, re.time, re.number, re.space, re.email, re.punctuation
  ];
}
```
- example usage
```shell
...

'$ npm install pos'

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
var taggedWord = taggedWords[i];
var word = taggedWord[0];
var tag = taggedWord[1];
console.log(word + " /" + tag);
...
```



# <a name="apidoc.module.pos.Lexer.prototype"></a>[module pos.Lexer.prototype](#apidoc.module.pos.Lexer.prototype)

#### <a name="apidoc.element.pos.Lexer.prototype.lex"></a>[function <span class="apidocSignatureSpan">pos.Lexer.prototype.</span>lex (string)](#apidoc.element.pos.Lexer.prototype.lex)
- description and source-code
```javascript
lex = function (string){
  var array = []
    , node = new LexerNode(string, this.regexs[0], this.regexs.slice(1));

  node.fillArray(array);
  return array;
}
```
- example usage
```shell
...

'$ npm install pos'

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
var taggedWord = taggedWords[i];
var word = taggedWord[0];
var tag = taggedWord[1];
console.log(word + " /" + tag);
...
```



# <a name="apidoc.module.pos.Tagger"></a>[module pos.Tagger](#apidoc.module.pos.Tagger)

#### <a name="apidoc.element.pos.Tagger.Tagger"></a>[function <span class="apidocSignatureSpan">pos.</span>Tagger ()](#apidoc.element.pos.Tagger.Tagger)
- description and source-code
```javascript
function POSTagger(){
    this.lexicon = require('./lexicon');
}
```
- example usage
```shell
...
'$ npm install pos'

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
    var taggedWord = taggedWords[i];
    var word = taggedWord[0];
    var tag = taggedWord[1];
    console.log(word + " /" + tag);
}
...
```



# <a name="apidoc.module.pos.Tagger.prototype"></a>[module pos.Tagger.prototype](#apidoc.module.pos.Tagger.prototype)

#### <a name="apidoc.element.pos.Tagger.prototype.extendLexicon"></a>[function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>extendLexicon (lexicon)](#apidoc.element.pos.Tagger.prototype.extendLexicon)
- description and source-code
```javascript
extendLexicon = function (lexicon) {
  for (var word in lexicon) {
    if (!this.lexicon.hasOwnProperty(word)) {
      this.lexicon[word] = lexicon[word];
    }
  }
}
```
- example usage
```shell
...
    var taggedWord = taggedWords[i];
    var word = taggedWord[0];
    var tag = taggedWord[1];
    console.log(word + " /" + tag);
}

// extend the lexicon
tagger.extendLexicon({'Obama': ['NNP']});
tagger.tag(['Mr', 'Obama']);
// --> [[ 'Mr', 'NNP' ], [ 'Obama', 'NNP' ]]
'''

ACKNOWLEDGEMENTS:

Thanks to Mark Watson for writing FastTag, which served as the basis for jspos.
...
```

#### <a name="apidoc.element.pos.Tagger.prototype.prettyPrint"></a>[function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>prettyPrint (taggedWords)](#apidoc.element.pos.Tagger.prototype.prettyPrint)
- description and source-code
```javascript
prettyPrint = function (taggedWords) {
	for (i in taggedWords) {
        print(taggedWords[i][0] + "(" + taggedWords[i][1] + ")");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pos.Tagger.prototype.tag"></a>[function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>tag (words)](#apidoc.element.pos.Tagger.prototype.tag)
- description and source-code
```javascript
tag = function (words) {
  var taggedSentence = new Array(words.length);

  // Initialise taggedSentence with words and initial categories
  for (var i = 0, size = words.length; i < size; i++) {
    taggedSentence[i] = new Array(2);
    taggedSentence[i][0] = words[i];
    // lexicon maps a word to an array of possible categories
    var ss = this.lexicon[words[i]];
    // 1/22/2002 mod (from Lisp code): if not in hash, try lower case:
    if (!ss)
      ss = this.lexicon[words[i].toLowerCase()];
    if (!ss && (words[i].length === 1))
      taggedSentence[i][1] = words[i] + "^";
    // We need to catch scenarios where we pass things on the prototype
    // that aren't in the lexicon: "constructor" breaks this otherwise
    if (!ss || (Object.prototype.toString.call(ss) !== '[object Array]'))
      taggedSentence[i][1] = "NN";
    else
      taggedSentence[i][1] = ss[0];
  }

  // Apply transformation rules
  taggedSentence.forEach(function(taggedWord, index) {
    transformationRules.getRules().forEach(function(rule) {
      rule(taggedSentence, index);
    });
  });
  return taggedSentence;
}
```
- example usage
```shell
...

USAGE:

'''javascript
var pos = require('pos');
var words = new pos.Lexer().lex('This is some sample text. This text can contain multiple sentences.');
var tagger = new pos.Tagger();
var taggedWords = tagger.tag(words);
for (i in taggedWords) {
    var taggedWord = taggedWords[i];
    var word = taggedWord[0];
    var tag = taggedWord[1];
    console.log(word + " /" + tag);
}
...
```

#### <a name="apidoc.element.pos.Tagger.prototype.wordInLexicon"></a>[function <span class="apidocSignatureSpan">pos.Tagger.prototype.</span>wordInLexicon (word)](#apidoc.element.pos.Tagger.prototype.wordInLexicon)
- description and source-code
```javascript
wordInLexicon = function (word){
    var ss = this.lexicon[word];
    if (ss != null)
        return true;
    // 1/22/2002 mod (from Lisp code): if not in hash, try lower case:
    if (!ss)
        ss = this.lexicon[word.toLowerCase()];
    if (ss)
        return true;
    return false;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
