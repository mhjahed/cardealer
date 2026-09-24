<!-- CAR DEALER WEB · crimson #ef4444 on #0d1117 · widgets verified 2026-09-12 -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:ef4444&height=190&section=header&text=CAR%20DEALER&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=listings%20%C2%B7%20roles%20%C2%B7%20search%20%C2%B7%20rich%20pages%20%E2%80%94%20django&descSize=17&descAlignY=60" alt="Car Dealer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2600&pause=900&color=F87171&center=true&vCenter=true&width=760&height=95&lines=admin+%C2%B7+dealer+%C2%B7+customer+roles;listings+%C2%B7+brand%2Fprice%2Ftype+filtering;ckeditor+pages+%C2%B7+postgres-ready" alt="typing" />

<p>
  <img src="https://img.shields.io/badge/django-backend-0d1117?style=for-the-badge&logo=django&logoColor=44b78b" alt="django" />
  <img src="https://img.shields.io/badge/allauth-auth-0d1117?style=for-the-badge&logo=django&logoColor=ef4444" alt="allauth" />
  <img src="https://img.shields.io/badge/ckeditor-rich%20text-ef4444?style=for-the-badge&logo=ckeditor&logoColor=white" alt="ckeditor" />
  <img src="https://img.shields.io/badge/postgresql-prod-0d1117?style=for-the-badge&logo=postgresql&logoColor=336791" alt="postgres" />
  <img src="https://img.shields.io/badge/license-MIT-0d1117?style=for-the-badge&logoColor=f87171" alt="license" />
</p>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:ef4444,100:0d1117&height=3" alt="" />

## ▍$ cat listing.full

A modern, responsive dealership platform: three permission tiers, full listings
management, real-time search and filtering, and rich-text detail pages — wired
for production with Whitenoise static handling and a PostgreSQL-ready backend.

```yaml
roles   : admin (everything) · dealer (own inventory) · customer (browse/search)
search  : dynamic — filter by brand · model · price band · body type
content : ckeditor-powered rich descriptions per vehicle
db      : sqlite (dev) · postgresql (prod) via django orm
deploy  : whitenoise · production settings · heroku-ready
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:ef4444,100:0d1117&height=3" alt="" />

## ▍$ ls features/

▸ **auth & roles** — signup / login / logout with admin, dealer, customer scopes
▸ **listings management** — add, edit, delete vehicles (admin & dealer)
▸ **search & filtering** — brand, model, price, type — dynamic, client-side reactive
▸ **detail pages** — image galleries + full specifications + ckeditor content
▸ **responsive ui** — mobile-first; seamless from phone to showroom screen
▸ **production config** — static files, security posture, deploy docs

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:ef4444,100:0d1117&height=3" alt="" />

## ▍$ cat stack.json

<div align="center">
  <img src="https://skillicons.dev/icons?i=django,py,postgres,sqlite,bootstrap,js,html,css&perline=9" alt="stack" />
</div>

<br/>

| PIECE | TECH |
|---|---|
| backend | Python · Django · django-allauth |
| rich text | django-ckeditor *(upgrade to CKEditor 5 advised for prod)* |
| fields | django-multiselectfield |
| assets | django-js-asset · whitenoise |
| db | sqlite · postgresql (`psycopg2-binary` on windows) |
| frontend | HTML5 · CSS3 · JavaScript · Bootstrap |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:ef4444,100:0d1117&height=3" alt="" />

## ▍$ ./setup

```bash
git clone https://github.com/mhjahed/cardealer.git && cd cardealer
python -m venv .venv && source .venv/bin/activate   # windows: .venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser                    # optional
python manage.py runserver                          # → http://127.0.0.1:8000
```

## ▍$ tree .

```
CarDealerWeb/
├── cardealer/        models · views · urls
│   ├── templates/    html views
│   └── static/       css · js · images
├── manage.py
└── requirements.txt
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:ef4444,100:0d1117&height=3" alt="" />

## ▍$ grep -i next roadmap.txt

- ▸ payment gateway — reserve a car online
- ▸ real-time customer ↔ dealer chat
- ▸ recommendation engine (ml-assisted)
- ▸ email notifications on status changes

<br/>

<div align="center">

`built end-to-end by` **[MH JAHED](https://github.com/mhjahed)** · `mhjahed@proton.me`

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ef4444,100:0d1117&height=110&section=footer" alt="" />
