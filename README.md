# Первая задача находится по ссылке :

# Для решения второй задачи подойдет код : 

SELECT
    TO_CHAR(DATE_TRUNC('MONTH', CURRENT_DATE) + (n || ' months')::INTERVAL, 'Month') AS month,
    EXTRACT(DAY FROM (DATE_TRUNC('MONTH', CURRENT_DATE) + (n || ' months')::INTERVAL + '1 month'::INTERVAL) - '1 day'::INTERVAL) AS days
FROM generate_series(0, 11) n;


# Для решения третей задачи подойдет код : 
<script>
    document.addEventListener('DOMContentLoaded', function () {
        console.log('Страница полностью загружена.');
    });
</script>