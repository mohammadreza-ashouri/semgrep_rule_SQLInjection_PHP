# semgrep_rule_SQLInjection_PHP

Semgrep is a powerful static code analyzer that supports for many languages. Nevertheless,  in PHP it is still experimental, and at the time of writing this rule, there was not any SQL injection rule for semgrep, so I wrote this.



semgrep --config sql-injection-php.yaml --lang=php .
