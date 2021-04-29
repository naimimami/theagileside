


# Decomposition Strategies
- [x] Decomposition by business capability, sub-capability pattern
Define services corresponding to Domain-Driven Design (DDD) subdomains. DDD refers to the application’s problem space - the business - as the domain. A domain is consists of multiple subdomains. Each subdomain corresponds to a different part of the business.
- [x] Decomposition by subdomain pattern / bounded context pattern
- [x] Decomposition by use case pattern
- [x] Decomposition by resources pattern
- [x] Decomposition by volatility





**GetGoal**


- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item



First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column





















ctrl-shift-m


https://www.markdownguide.org/basic-syntax/

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

Heading level 1
===============

I think I'll use it to format all of my documents from now on.

This is the first line.
And this is the second line.


First line with two spaces after.
And the next line.

First line with the HTML tag after.<br>
And the next line.

> Dorothy followed her through many of the beautiful rooms in her castle.


> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with


> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.



1. First item
2. Second item
3. Third item
4. Fourth item



- First item
- Second item
- Third item
- Fourth item

* Main Topic
    * Subtopic1

        Some Points for subtopic1

    * Subtopic2

        Some Points for subtopic2




*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.


1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.


At the command prompt, type `nano`.



``Use `code` in your Markdown file.``


***

---

_________________



Try to put a blank line before...

---

...and after a horizontal rule.


I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).


```ruby
def index
  puts "hello world"
end
```


```java
public void deleteEntity(@PathVariable(value = "id") String id) {
  try {
    this.getService().deleteEntityById(id);
  } catch (Exception e) {
    String error = MessageFormat.format(" something happened {0} {1}", e.getMessage(), e.getMessage());
    this.logger.info(error);
    // throw new Exception(error);
  }
}
```

```sql
    DROP DATABASE IF EXISTS designer_db;
    CREATE DATABASE IF NOT EXISTS designer_db;
    USE designer_db;
    -- ---------------
    SHOW WARNINGS;
    -- ---------------
    create table document_type (
        id varchar(80) not null
        , name varchar(80) not null
        , constraint pk_document_type primary key (id)
    );
```

```yaml
    def index
      puts "hello world"
    end
```

```html
    <html>
      <head>
      </head>
    </html>
```





This is a regular paragraph.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

This is another regular paragraph.



| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |



```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```



```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.



### My Great Heading {#custom-id}





First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.





- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media






bash ('*.sh', '*.ksh', '*.bash', '*.ebuild', '*.eclass')
bat ('*.bat', '*.cmd')
c ('*.c', '*.h')
cpp ('*.cpp', '*.hpp', '*.c++', '*.h++', '*.cc', '*.hh', '*.cxx', '*.hxx', '*.pde')
css ('*.css')
go ('*.go')
html ('*.html', '*.htm', '*.xhtml', '*.xslt')
java ('*.java')
js ('*.js')
jsp ('*.jsp')
markdown ('*.md')
php ('*.php', '*.php(345)')
protobuf ('*.proto')
py3tb ('*.py3tb')
pytb ('*.pytb')
python ('*.py', '*.pyw', '*.sc', 'SConstruct', 'SConscript', '*.tac')
rb ('*.rb', '*.rbw', 'Rakefile', '*.rake', '*.gemspec', '*.rbx', '*.duby')
scala ('*.scala')
sql ('*.sql')
sqlite3 ('*.sqlite3-console')
text ('*.txt')
velocity ('*.vm', '*.fhtml')
xml ('*.xml', '*.xsl', '*.rss', '*.xslt', '*.xsd', '*.wsdl')
xquery ('*.xqy', '*.xquery')
xslt ('*.xsl', '*.xslt')
yaml ('*.yaml', '*.yml')







ctrl-shift-m


https://www.markdownguide.org/basic-syntax/

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

Heading level 1
===============

I think I'll use it to format all of my documents from now on.

This is the first line.
And this is the second line.


First line with two spaces after.
And the next line.

First line with the HTML tag after.<br>
And the next line.

> Dorothy followed her through many of the beautiful rooms in her castle.


> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with


> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.



1. First item
2. Second item
3. Third item
4. Fourth item



- First item
- Second item
- Third item
- Fourth item

* Main Topic
    * Subtopic1

        Some Points for subtopic1

    * Subtopic2

        Some Points for subtopic2




*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.


1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.


At the command prompt, type `nano`.



``Use `code` in your Markdown file.``


***

---

_________________



Try to put a blank line before...

---

...and after a horizontal rule.


I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).


```ruby
def index
  puts "hello world"
end
```


```java
public void deleteEntity(@PathVariable(value = "id") String id) {
  try {
    this.getService().deleteEntityById(id);
  } catch (Exception e) {
    String error = MessageFormat.format(" something happened {0} {1}", e.getMessage(), e.getMessage());
    this.logger.info(error);
    // throw new Exception(error);
  }
}
```

```sql
    DROP DATABASE IF EXISTS designer_db;
    CREATE DATABASE IF NOT EXISTS designer_db;
    USE designer_db;
    -- ---------------
    SHOW WARNINGS;
    -- ---------------
    create table document_type (
        id varchar(80) not null
        , name varchar(80) not null
        , constraint pk_document_type primary key (id)
    );
```

```yaml
    def index
      puts "hello world"
    end
```

```html
    <html>
      <head>
      </head>
    </html>
```





This is a regular paragraph.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

This is another regular paragraph.



| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |



```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```



```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.



### My Great Heading {#custom-id}





First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.





- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
