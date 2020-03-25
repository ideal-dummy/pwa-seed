### Clone Project Locally

```ssh
git clone git@github.com:idealdummy/pwa-seed.git
```

### Fetch and Checkout Develop Brancbh

TODO: Create develop branch so in the future this can be done

```ssh
git fetch; git checkout develop;
```

### Move into root directory

```ssh
cd pwa-seed
```

### Create Environment Variables

#### Root Environment

```
cp .env.example .env
```

#### Server Environment

```ssh
cp server/.env.example server/.env
```

### Install Dependencies

#### Root

```ssh
npm install;
```

#### Server

```ssh
cd server;
npm install;
```

#### Client

```ssh
cd client;
npm install;
```

### Docker Compose

```ssh
docker-compose up
```

### Hope for the best
