---
description: 'To get started, follow these steps to install the necessary components:'
---

# Installation

1. **Clone the Repository**:

```powershell
git clone https://github.com/vuvu15202/PGEA.git
```

2. **Install Dependencies**:

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXduCPUDA_r-ePq9JtRmbEaIjDwnDpLcB0BJZfhFGPc8KPXUjS08FSAVSVOyqGB7H300m-tWdvRdBVq54j1IQ7DHd2oMu74V67hZGZnExyYY-Rp4NPF5XY3pKxhU3YHfbiX3C38IW62d1OiJ8AM-5QMTeTarWLR0od67GX1Nww?key=CZ89Z8QbD4X9YTRzADcgIQ" alt=""><figcaption></figcaption></figure>

* For both BE and FE

```powershell
npm install
```

* For FE

```powershell
nvm install 18.17.0
```

```powershell
nvm use  18.17.0
```

* For BE

```
npm install sails -g
```

3. **Configure BE Database**:

<figure><img src="../.gitbook/assets/Screenshot 2024-06-12 083908.png" alt=""><figcaption></figcaption></figure>

Change that code to config your database:

```javascript
default: {
    adapter: require('sails-mysql'),
    url: process.env.MYSQL_DB || 'mysql://root:your_root@localhost:3306/your_database_name'
  },
  // mongo: {
  //   adapter: "sails-mongo",
  //   url: process.env.MONGO_DB || "mongodb://acc:pass@host:27017/db",
  // }
```

If you user mongo database go to ![](<../.gitbook/assets/image (13).png>)  on Config folder and read the comment:&#x20;

````javascript
attributes: {
    id: {
      type: "number",
      columnType: "bigint",
      autoIncrement: true,
    },
    isDelete: {
      type: "boolean",
      defaultsTo: false,
    },
    createdBy: {
      // model: 'user'
      type: "string",
      allowNull: true,
    },
    deletedBy: {
      // model: 'user'
      type: "string",
      allowNull: true,
    },
    createdAt: {
      type: "number",
      autoCreatedAt: true,
    },
    updatedAt: {
      type: "number",
      autoUpdatedAt: true,
    },
    deletedAt: {
      type: "number",
      columnType: "bigint",
    },
    //--------------------------------------------------------------------------
    //  /\   Using MongoDB?
    //  ||   Replace `id` above with this instead:
    //
    // ```
    // id: { type: 'string', columnName: '_id' },
    // ```
    //
    // Plus, don't forget to configure MongoDB as your default datastore:
    // https://sailsjs.com/docs/tutorials/using-mongo-db
    //--------------------------------------------------------------------------
  },
````

**Start the Application**:

<pre class="language-powershell"><code class="lang-powershell"><strong>sails lift
</strong></code></pre>

or

```powershell
sails lift --drop
```

You can learn Sails.js CLI on [here](https://sailsjs.com/documentation/reference/command-line-interface).

4. **Configure FE to call BE Path:**&#x20;

<figure><img src="../../README/.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

**Start the Application**:

<pre><code><strong>npm run dev
</strong></code></pre>

You can learn Next.js CLI on [here](https://nextjs.org/docs/pages/api-reference/next-cli).

5. Database Installation

**Step 1:** See how to install it [here](https://www.youtube.com/watch?v=u96rVINbAUI).

**Step 2:** Run that script one by one to set up native password:

1. Alter USER 'root'@'localhost' IDENTIFIED WITH mysql\_native\_password BY 'your\_password';
2. GRANT ALL PRIVILEGES ON \*.\* TO 'root'@'localhost' WITH GRANT OPTION;
3. FLUSH PRIVILEGES;



\
