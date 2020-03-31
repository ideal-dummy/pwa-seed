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
yarn start
```
> this should kick off a yarn install in both the server and client folder. then start both directories to run together.

### Docker Compose

> this can be run after yarn start has been run on the root directory.

```ssh
docker-compose up --build
```

### Hope for the best
