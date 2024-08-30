What I learned this week was hardhat commads and a lit bit about redis. 

# The thing I learned about hardhat was: 
```

        it("Should be resolved", async function () {
          const { issue, karen2 } = await loadFixture(deployKarenFixture);
          await issue.connect(karen2).raiseVoice()
          expect(await issue.karrenSquadSize()).to.equal(1)
          await issue.connect(karen2).raiseVoice()
          expect(await issue.karrenSquadSize()).to.equal(1)

        });
```

# What I learned for redis is:

```

Basic CRUD operations
Set key value
Get key value
keys pattern

Using Arrays
Lpush array value
Rpush array value
Lpop array
Rpop array
Lrange array index -1

Working with expirations
expire key seconds
ttl key
set key value ex seconds
