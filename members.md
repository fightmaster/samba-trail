---
layout: post
title: Участники <span>«SAMBA TRAIL»/«САМБА ТРЕЙЛ»</span>
description: «САМБА ТРЕЙЛ» в Саратовской области. 70 и 32 км наедине с природой.
header_background_image: https://source.unsplash.com/0U_gjae2TKo/2000x1322?a=.png
newsletter_background_image: https://source.unsplash.com/c8ET5XvBwnU/2000x1322?a=.png
---

{% assign allMembers = 0 %}

<h3>«Ultra» 70.8 км 2170 D+, М18-М39</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mv18 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Ultra» 70.8 км 2170 D+, М40-М49</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mv40 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Ultra» 70.8 км 2170 D+, М50+</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mv50 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Ultra» 70.8 км 2170 D+, Ж18-Ж39</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mw18 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Ultra» 70.8 км 2170 D+, Ж40-Ж49</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mw40 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Ultra» 70.8 км 2170 D+, Ж50+</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.70mw50 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>


<h3>«Trail» 36.3 км 1300 D+, М18-М39</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mv18 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Trail» 36.3 км 1300 D+, М40-М49</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mv40 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Trail» 36.3 км 1300 D+, М50+</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mv50 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Trail» 36.3 км 1300 D+, Ж18-Ж39</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mw18 %}
        {% assign counter=counter | plus:1 %}   
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Trail» 36.3 км 1300 D+, Ж40-Ж49</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mw40 %}
        {% assign counter=counter | plus:1 %}
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>

<h3>«Trail» 36.3 км 1300 D+, Ж50+</h3>
<div class="table-responsive">
    <table class="table table-bordered table-striped">
        <thead>
            <tr>
                <th>#</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Клуб</th>
                <th>Город</th>
                <th>Год</th>
            </tr>
        </thead>
        <tbody>
        {% assign counter = 0 %}
        {% for member in site.data.appl.32mw50 %}
        {% assign counter=counter | plus:1 %}
            <tr>
                <th scope="row">{{ member.number }}</th>
                <td>{{ member.firstName }}</td>
                <td>{{ member.lastName }}</td>
                <td>{{ member.club }}</td>
                <td>{{ member.city }}</td>
                <td>{{ member.year }}</td>
            </tr>
        {% endfor %}
            <tr>
                <td colspan="6">Количество заявок: {{ counter }}</td>
            </tr>
        </tbody>
    </table>
</div>
