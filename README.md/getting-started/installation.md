---
description: 'To get started, follow these steps to install the necessary components:'
---

# Installation

1. **Clone the Repository**:

```powershell
git clone https://github.com/your-repo/admin-page-builder.git
cd admin-page-builder
```

2. **Install Dependencies**:

* For both BE and FE

```powershell
npm install
```

3. **Configure Database**:

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

4. **Start the Application**:

```powershell
sails lift
```

or

```powershell
sails lift --drop
```

You can learn Sails.js CLI on [here](https://sailsjs.com/documentation/reference/command-line-interface).
