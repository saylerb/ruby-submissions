# <Team Members>

**Instructor:**

**Repo Url:**

## Notes

## Evaluation Rubric

### 1. Functional Expectations

Score: 4

* Iterations 0-4 pass
* Additional features:
  * Reads JSON
  * Graphs of the data [example](http://chart.apis.google.com/chart?chco=FFF804,336699,339933,ff0000,cc99cc,cf5910&chf=bg,s,FFFFFF&chd=s:AojV1uyTYhueeI9&chl=Shopin1901%7CCandisart%7CMiniatureBikez%7CGoldenRayPress%7CGoldenHelmets%7CUrcase17%7CVenmo%7CSkype%7CJohnson%7CEllo%7CHidy%7CBhyd%7CLair%7CHelm%7CGot&chtt=All+Merchants+by+Revenue&cht=p&chs=750x375&chxr=0,0,0.8066154E5)

* 4: Application implements iterations 0, 1, 2, 3, (4 or 5), and features of your own design
* 3: Application implements iterations 0, 1, 2, 3, and either 4 or 5
* 2: Application implements iterations 0, 1, 2, and 3
* 1: Application does not fully implement iterations 0, 1, 2, and 3

### 2. Test-Driven Development

Score: 4

* CI (passes ;)
* Tests pass

  ```
  Finished in 3.08 seconds (files took 0.39026 seconds to load)
  141 examples, 0 failures
  ```
* 97% code coverage
* You can get code coverage to ignore test files by starting it like this:

  Old:

  ```ruby
  SimpleCov.start
  ```

  New:

  ```ruby
  SimpleCov.start do
    add_filter "/spec/"
  end
  ```

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
* 2: Application makes some use of tests, but the coverage is insufficient
* 1: Application does not demonstrate strong use of TDD

### 3. Encapsulation / Breaking Logic into Components

Score: 3

* Nice job being able to handle both JSON and CSV
* Avoid doing the job of the repo, eg the test doing `repo.all << Item.new(data)`,
  that's why the repo exists :) by pushing all such knowledge / responsibility into
  the repo, the rest of the codebase is protected from any volatility in its innternals

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 4. Fundamental Ruby & Style

Score: 3

* No issues

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 5. Enumerable & Collections

Score: 3

* Didn't see any issues

* 4: Application consistently makes use of the best-choice Enumerable methods
* 3: Application demonstrates comfortable use of appropriate Enumerable methods
* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques
* 1: Application demonstrates deficiencies with Enumerable and struggles with collections
