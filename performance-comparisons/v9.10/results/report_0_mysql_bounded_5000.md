### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 1ms | 6ms | 5ms | 567.42
| StatusStore.UpdateExpiredDNDStatuses | avg | 2ms | 6ms | 4ms | 232.07
| PostStore.GetPostReminders | avg | 3ms | 6ms | 3ms | 86.71
| JobStore.Save | avg | 2ms | 4ms | 2ms | 86.54
| StatusStore.SaveOrUpdate | avg | 19ms | 26ms | 7ms | 36.69
| PostStore.SearchPostsForUser | avg | 43ms | 55ms | 12ms | 28.09
| ChannelStore.UpdateSidebarCategories | avg | 23ms | 28ms | 5ms | 21.54
| ChannelStore.GetTeamChannels | avg | 33ms | 37ms | 4ms | 12.10
| UserStore.AnalyticsActiveCount | avg | 205ms | 217ms | 12ms | 5.84
| TeamStore.GetActiveMemberCount | avg | 152ms | 157ms | 5ms | 3.29
| TeamStore.GetTotalMemberCount | avg | 117ms | 119ms | 2ms | 1.72
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | p99 | 5ms | 25ms | 20ms | 404.04
| ChannelStore.AnalyticsTypeCount | p99 | 5ms | 24ms | 19ms | 383.84
| JobStore.Save | p99 | 5ms | 19ms | 14ms | 282.83
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 141.18
| PostStore.GetPostReminders | p99 | 10ms | 22ms | 12ms | 123.50
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.UpdateSidebarCategories | p99 | 49ms | 93ms | 44ms | 88.94
| FileInfoStore.Save | p99 | 9ms | 16ms | 7ms | 75.29
| ComplianceStore.MessageExport | p99 | 5ms | 7ms | 2ms | 40.40
| FileInfoStore.AttachToPost | p99 | 10ms | 14ms | 4ms | 40.16
| StatusStore.SaveOrUpdate | p99 | 232ms | 300ms | 68ms | 29.28
| ProductNoticesStore.View | p99 | 120ms | 153ms | 33ms | 27.46
| UserStore.GetByUsername | p99 | 24ms | 30ms | 6ms | 24.74
| PostStore.SearchPostsForUser | p99 | 241ms | 250ms | 9ms | 3.73
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.SaveOrUpdate | avg | 2ms | 0s | -2ms | -132.63
| SystemStore.PermanentDeleteByName | avg | 2ms | 0s | -2ms | -108.60
| FileInfoStore.GetByIds | avg | 5ms | 0s | -5ms | -103.89
| BotStore.Save | avg | 17ms | 0s | -17ms | -102.54
| FileInfoStore.Search | avg | 18ms | 0s | -18ms | -98.52
| UserStore.GetMany | avg | 31ms | 2ms | -29ms | -93.01
| SessionStore.GetSessionsExpired | avg | 53ms | 8ms | -45ms | -84.63
| JobStore.Get | avg | 9ms | 2ms | -7ms | -78.41
| ChannelStore.GetChannelsByUser | avg | 46ms | 12ms | -34ms | -73.22
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 15ms | 5ms | -10ms | -68.81
| PluginStore.List | avg | 6ms | 2ms | -4ms | -68.31
| LinkMetadataStore.Get | avg | 5ms | 2ms | -3ms | -65.71
| ChannelStore.Get | avg | 12ms | 4ms | -8ms | -65.39
| ChannelStore.GetMemberLastViewedAt | avg | 14ms | 5ms | -9ms | -63.40
| TeamStore.GetAllPage | avg | 16ms | 6ms | -10ms | -63.38
| ChannelStore.GetGuestCount | avg | 21ms | 8ms | -13ms | -62.71
| ThreadStore.GetTotalUnreadThreads | avg | 13ms | 5ms | -8ms | -62.45
| TeamStore.GetTeamsForUser | avg | 16ms | 6ms | -10ms | -62.30
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 50ms | 19ms | -31ms | -61.89
| ThreadStore.GetTotalThreads | avg | 13ms | 5ms | -8ms | -61.03
| ThreadStore.GetTeamsUnreadForUser | avg | 15ms | 6ms | -9ms | -60.91
| PostStore.GetPostReminderMetadata | avg | 5ms | 2ms | -3ms | -60.55
| UserTermsOfServiceStore.GetByUser | avg | 17ms | 7ms | -10ms | -60.05
| PostStore.GetPostsAfter | avg | 8ms | 3ms | -5ms | -59.91
| UserStore.IsEmpty | avg | 10ms | 4ms | -6ms | -59.80
| SessionStore.GetLRUSessions | avg | 17ms | 7ms | -10ms | -59.78
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 13ms | 5ms | -8ms | -59.66
| ChannelStore.GetChannelUnread | avg | 5ms | 2ms | -3ms | -59.56
| JobStore.GetAllByStatus | avg | 7ms | 3ms | -4ms | -57.51
| ChannelStore.GetMembersForUser | avg | 9ms | 4ms | -5ms | -56.99
| ChannelStore.GetChannels | avg | 9ms | 4ms | -5ms | -56.79
| ChannelStore.CreateDirectChannel | avg | 39ms | 17ms | -22ms | -56.45
| TeamStore.GetChannelUnreadsForAllTeams | avg | 14ms | 6ms | -8ms | -55.71
| TeamStore.GetTeamsByUserId | avg | 16ms | 7ms | -9ms | -54.78
| GroupStore.GetByName | avg | 15ms | 7ms | -8ms | -54.11
| PreferenceStore.GetAll | avg | 20ms | 9ms | -11ms | -53.85
| ThreadStore.GetMembershipForUser | avg | 6ms | 3ms | -3ms | -53.77
| TeamStore.Get | avg | 6ms | 3ms | -3ms | -53.51
| FileInfoStore.GetForPost | avg | 4ms | 2ms | -2ms | -52.53
| ThreadStore.GetTotalUnreadMentions | avg | 11ms | 5ms | -6ms | -52.35
| StatusStore.Get | avg | 13ms | 6ms | -7ms | -52.26
| PostPersistentNotificationStore.GetSingle | avg | 6ms | 3ms | -3ms | -51.85
| PostStore.GetPosts | avg | 17ms | 8ms | -9ms | -51.73
| SessionStore.Get | avg | 18ms | 9ms | -9ms | -51.35
| PostPriorityStore.GetForPosts | avg | 8ms | 4ms | -4ms | -51.01
| PostAcknowledgementStore.GetForPosts | avg | 8ms | 4ms | -4ms | -51.01
| PostStore.GetEtag | avg | 12ms | 6ms | -6ms | -50.91
| GroupStore.GetGroups | avg | 8ms | 4ms | -4ms | -50.58
| ChannelStore.GetByName | avg | 14ms | 7ms | -7ms | -50.31
| UserStore.GetForLogin | avg | 16ms | 8ms | -8ms | -49.19
| ThreadStore.GetThreadFollowers | avg | 6ms | 3ms | -3ms | -49.00
| ChannelStore.GetPinnedPostCount | avg | 6ms | 3ms | -3ms | -47.68
| UserStore.GetUnreadCount | avg | 6ms | 3ms | -3ms | -47.58
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 4ms | 2ms | -2ms | -47.36
| ThreadStore.GetThreadForUser | avg | 9ms | 5ms | -4ms | -46.79
| ChannelStore.SaveMember | avg | 80ms | 44ms | -36ms | -45.09
| SessionStore.Save | avg | 20ms | 11ms | -9ms | -44.15
| ChannelStore.GetMemberForPost | avg | 5ms | 3ms | -2ms | -43.69
| PostStore.GetSingle | avg | 5ms | 3ms | -2ms | -43.01
| UserStore.GetAllProfiles | avg | 12ms | 7ms | -5ms | -40.43
| ChannelStore.Save | avg | 18ms | 11ms | -7ms | -39.90
| UserStore.GetProfilesByUsernames | avg | 5ms | 3ms | -2ms | -38.01
| PreferenceStore.Get | avg | 5ms | 3ms | -2ms | -37.24
| PostStore.Get | avg | 8ms | 5ms | -3ms | -37.02
| JobStore.GetCountByStatusAndType | avg | 5ms | 3ms | -2ms | -37.00
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 5ms | 3ms | -2ms | -36.87
| EmojiStore.GetByName | avg | 5ms | 3ms | -2ms | -36.85
| ChannelStore.GetFileCount | avg | 8ms | 5ms | -3ms | -36.84
| ReactionStore.GetForPost | avg | 6ms | 4ms | -2ms | -33.56
| PostPriorityStore.GetForPost | avg | 6ms | 4ms | -2ms | -33.39
| ChannelStore.GetPublicChannelsForTeam | avg | 18ms | 12ms | -6ms | -33.09
| PostAcknowledgementStore.GetForPost | avg | 6ms | 4ms | -2ms | -32.05
| ThreadStore.GetThreadsForUser | avg | 6ms | 4ms | -2ms | -31.82
| ChannelStore.SearchGroupChannels | avg | 6ms | 4ms | -2ms | -31.51
| ChannelStore.GetAllChannelMembersForUser | avg | 13ms | 9ms | -4ms | -31.10
| ChannelStore.CreateInitialSidebarCategories | avg | 28ms | 20ms | -8ms | -28.35
| WebhookStore.GetOutgoingByTeam | avg | 7ms | 5ms | -2ms | -28.18
| PostStore.GetPostsBefore | avg | 7ms | 5ms | -2ms | -26.81
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 16ms | 12ms | -4ms | -25.09
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 18ms | 14ms | -4ms | -22.75
| JobStore.GetNewestJobByStatusesAndType | avg | 9ms | 7ms | -2ms | -22.58
| PostStore.GetPostsSince | avg | 12ms | 10ms | -2ms | -16.55
| ChannelStore.GetMemberCount | avg | 186ms | 158ms | -28ms | -15.09
| ChannelStore.AutocompleteInTeamForSearch | avg | 137ms | 126ms | -11ms | -8.05
| ChannelStore.Autocomplete | avg | 1.6s | 1.476s | -124ms | -7.75
| TeamStore.SaveMember | avg | 108ms | 100ms | -8ms | -7.41
| UserStore.Count | avg | 122ms | 114ms | -8ms | -6.56
| UserStore.GetAllProfilesInChannel | avg | 504ms | 477ms | -27ms | -5.36
| UserStore.Search | avg | 95ms | 91ms | -4ms | -4.21
| UserStore.AutocompleteUsersInChannel | avg | 206ms | 200ms | -6ms | -2.92
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.GetByIds | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 25ms | 0s | -25ms | -100.60
| FileInfoStore.Search | p99 | 25ms | 0s | -25ms | -100.60
| UserStore.GetMany | p99 | 244ms | 5ms | -239ms | -97.95
| PostStore.GetPostsAfter | p99 | 205ms | 5ms | -200ms | -97.56
| ChannelStore.GetChannelUnread | p99 | 202ms | 5ms | -197ms | -97.52
| ChannelStore.CreateDirectChannel | p99 | 740ms | 70ms | -670ms | -90.54
| JobStore.Get | p99 | 295ms | 28ms | -267ms | -90.52
| SessionStore.GetSessionsExpired | p99 | 487ms | 48ms | -439ms | -90.05
| PluginStore.List | p99 | 196ms | 20ms | -176ms | -89.80
| PostStore.GetPostReminderMetadata | p99 | 47ms | 5ms | -42ms | -88.89
| FileInfoStore.GetForPost | p99 | 78ms | 9ms | -69ms | -88.60
| FileInfoStore.Get | p99 | 55ms | 9ms | -46ms | -84.19
| ChannelStore.GetPinnedPostCount | p99 | 201ms | 32ms | -169ms | -84.18
| UserStore.GetUnreadCount | p99 | 141ms | 24ms | -117ms | -83.21
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 98ms | 19ms | -79ms | -80.57
| PostStore.GetSingle | p99 | 100ms | 21ms | -79ms | -79.00
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 196ms | 42ms | -154ms | -78.57
| LinkMetadataStore.Get | p99 | 106ms | 23ms | -83ms | -78.41
| UserAccessTokenStore.GetByToken | p99 | 22ms | 5ms | -17ms | -78.34
| ThreadStore.GetThreadForUser | p99 | 201ms | 44ms | -157ms | -78.09
| JobStore.GetCountByStatusAndType | p99 | 102ms | 23ms | -79ms | -77.83
| ChannelStore.Save | p99 | 204ms | 48ms | -156ms | -76.38
| JobStore.UpdateStatusOptimistically | p99 | 19ms | 5ms | -14ms | -75.48
| PostAcknowledgementStore.GetForPosts | p99 | 190ms | 47ms | -143ms | -75.43
| PostStore.GetPostsByThread | p99 | 40ms | 10ms | -30ms | -74.86
| ReactionStore.GetForPost | p99 | 96ms | 25ms | -71ms | -74.17
| TeamStore.Get | p99 | 147ms | 38ms | -109ms | -74.17
| PostPriorityStore.GetForPosts | p99 | 194ms | 52ms | -142ms | -73.31
| ChannelStore.GetFileCount | p99 | 174ms | 47ms | -127ms | -73.03
| ThreadStore.GetMembershipForUser | p99 | 147ms | 40ms | -107ms | -72.98
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 142ms | 40ms | -102ms | -71.87
| ChannelStore.GetAllChannelMembersForUser | p99 | 165ms | 47ms | -118ms | -71.35
| ThreadStore.GetThreadFollowers | p99 | 170ms | 49ms | -121ms | -71.28
| PreferenceStore.Get | p99 | 137ms | 42ms | -95ms | -69.32
| JobStore.GetAllByStatus | p99 | 190ms | 60ms | -130ms | -68.38
| PostStore.GetPostsBefore | p99 | 165ms | 53ms | -112ms | -68.02
| ThreadStore.GetThreadsForUser | p99 | 155ms | 50ms | -105ms | -67.65
| PostPersistentNotificationStore.GetSingle | p99 | 150ms | 49ms | -101ms | -67.12
| WebhookStore.GetOutgoingByTeam | p99 | 135ms | 45ms | -90ms | -66.86
| UserStore.GetProfilesByUsernames | p99 | 121ms | 40ms | -81ms | -66.67
| GroupStore.GetGroups | p99 | 193ms | 65ms | -128ms | -66.21
| StatusStore.GetByIds | p99 | 24ms | 8ms | -16ms | -65.98
| EmojiStore.GetByName | p99 | 144ms | 49ms | -95ms | -65.93
| UserStore.Get | p99 | 80ms | 28ms | -52ms | -65.22
| ChannelStore.GetMembersForUser | p99 | 194ms | 69ms | -125ms | -64.37
| PostStore.Get | p99 | 168ms | 60ms | -108ms | -64.24
| ChannelStore.Get | p99 | 225ms | 81ms | -144ms | -63.93
| ChannelStore.GetMemberLastViewedAt | p99 | 225ms | 85ms | -140ms | -62.25
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 229ms | 88ms | -141ms | -61.66
| ThreadStore.GetTeamsUnreadForUser | p99 | 232ms | 89ms | -143ms | -61.64
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 222ms | 85ms | -137ms | -61.59
| ThreadStore.GetTotalThreads | p99 | 221ms | 85ms | -136ms | -61.41
| ThreadStore.GetTotalUnreadThreads | p99 | 217ms | 84ms | -133ms | -61.19
| ChannelStore.GetChannels | p99 | 198ms | 77ms | -121ms | -60.99
| StatusStore.Get | p99 | 224ms | 88ms | -136ms | -60.71
| UserStore.IsEmpty | p99 | 191ms | 75ms | -116ms | -60.57
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 227ms | 90ms | -137ms | -60.43
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 627ms | 249ms | -378ms | -60.29
| ThreadStore.GetTotalUnreadMentions | p99 | 211ms | 84ms | -127ms | -60.21
| PostStore.GetPosts | p99 | 228ms | 91ms | -137ms | -60.01
| PostPriorityStore.GetForPost | p99 | 154ms | 62ms | -92ms | -59.74
| TeamStore.GetTeamsForUser | p99 | 235ms | 95ms | -140ms | -59.64
| ChannelStore.GetMemberForPost | p99 | 96ms | 40ms | -56ms | -58.45
| TeamStore.GetAllPage | p99 | 231ms | 97ms | -134ms | -58.13
| RoleStore.ChannelHigherScopedPermissions | p99 | 19ms | 8ms | -11ms | -57.86
| ClusterDiscoveryStore.SetLastPingAt | p99 | 28ms | 12ms | -16ms | -57.66
| ThreadStore.GetThreadUnreadReplyCount | p99 | 47ms | 20ms | -27ms | -56.88
| GroupStore.GetByName | p99 | 231ms | 100ms | -131ms | -56.67
| ChannelStore.GetByName | p99 | 219ms | 96ms | -123ms | -56.20
| PostStore.GetEtag | p99 | 223ms | 98ms | -125ms | -56.10
| ChannelStore.SaveMember | p99 | 854ms | 382ms | -472ms | -55.30
| UserStore.GetAllProfiles | p99 | 190ms | 86ms | -104ms | -54.67
| PostStore.GetPostsSince | p99 | 172ms | 83ms | -89ms | -51.89
| TeamStore.GetTeamsByUserId | p99 | 234ms | 113ms | -121ms | -51.79
| PostStore.Update | p99 | 51ms | 25ms | -26ms | -50.98
| ChannelStore.SearchGroupChannels | p99 | 172ms | 85ms | -87ms | -50.54
| UserTermsOfServiceStore.GetByUser | p99 | 234ms | 117ms | -117ms | -50.05
| SessionStore.Save | p99 | 236ms | 121ms | -115ms | -48.80
| ChannelStore.GetPublicChannelsForTeam | p99 | 147ms | 77ms | -70ms | -47.51
| PostAcknowledgementStore.GetForPost | p99 | 154ms | 81ms | -73ms | -47.40
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.436s | 770ms | -666ms | -46.37
| SessionStore.Get | p99 | 232ms | 125ms | -107ms | -46.15
| UserStore.GetProfilesInChannel | p99 | 9ms | 5ms | -4ms | -44.20
| SessionStore.GetLRUSessions | p99 | 235ms | 135ms | -100ms | -42.49
| ChannelStore.GetGuestCount | p99 | 244ms | 141ms | -103ms | -42.15
| UserStore.GetForLogin | p99 | 235ms | 137ms | -98ms | -41.68
| ChannelStore.GetChannelsByUser | p99 | 276ms | 164ms | -112ms | -40.54
| TeamStore.SaveMember | p99 | 395ms | 247ms | -148ms | -37.45
| PreferenceStore.GetAll | p99 | 245ms | 159ms | -86ms | -35.16
| ChannelStore.Autocomplete | p99 | 7.504s | 4.935s | -2.569s | -34.24
| ChannelStore.GetMemberCount | p99 | 926ms | 668ms | -258ms | -27.86
| ChannelStore.CreateInitialSidebarCategories | p99 | 238ms | 177ms | -61ms | -25.64
| UserStore.AutocompleteUsersInChannel | p99 | 879ms | 660ms | -219ms | -24.92
| LinkMetadataStore.Save | p99 | 9ms | 7ms | -2ms | -21.56
| UserStore.GetProfileByIds | p99 | 22ms | 18ms | -4ms | -18.56
| UserStore.Search | p99 | 443ms | 368ms | -75ms | -16.93
| JobStore.GetNewestJobByStatusesAndType | p99 | 217ms | 194ms | -23ms | -10.60
| PostStore.GetPostIdAfterTime | p99 | 20ms | 18ms | -2ms | -9.81
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 22ms | 20ms | -2ms | -9.26
| UserStore.GetAllProfilesInChannel | p99 | 2.351s | 2.155s | -196ms | -8.34
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 99ms | 93ms | -6ms | -6.08
| PreferenceStore.Save | p99 | 48ms | 46ms | -2ms | -4.16
| UserStore.Count | p99 | 438ms | 428ms | -10ms | -2.29
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | avg | 217ms | 283ms | 66ms | 30.41
| createDirectChannel | avg | 201ms | 242ms | 41ms | 20.35
| addChannelMember | avg | 195ms | 227ms | 32ms | 16.39
| updateCategoriesForTeamForUser | avg | 33ms | 38ms | 5ms | 15.32
| searchPostsInTeam | avg | 54ms | 62ms | 8ms | 14.86
| getAnalytics | avg | 204ms | 230ms | 26ms | 12.74
| removeUserCustomStatus | avg | 125ms | 140ms | 15ms | 12.02
| createGroupChannel | avg | 328ms | 342ms | 14ms | 4.27
| getTeamStats | avg | 153ms | 159ms | 6ms | 3.93
| autocompleteUsers | avg | 166ms | 172ms | 6ms | 3.62
| createUser | avg | 136ms | 139ms | 3ms | 2.21
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | p99 | 249ms | 496ms | 247ms | 99.40
| searchPostsInTeam | p99 | 450ms | 485ms | 35ms | 7.79
| updateCategoriesForTeamForUser | p99 | 95ms | 97ms | 2ms | 2.10
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getDrafts | avg | 3ms | 0s | -3ms | -116.63
| searchFiles | avg | 21ms | 0s | -21ms | -101.98
| disablePlugin | avg | 235ms | 0s | -235ms | -99.84
| patchPost | avg | 2.379s | 41ms | -2.338s | -98.28
| setPostReminder | avg | 84ms | 15ms | -69ms | -81.85
| getChannelsForUser | avg | 48ms | 13ms | -35ms | -73.44
| getRolesByNames | avg | 4ms | 1ms | -3ms | -68.57
| getChannelUnread | avg | 6ms | 2ms | -4ms | -68.46
| getChannel | avg | 18ms | 6ms | -12ms | -68.16
| getCategoriesForTeamForUser | avg | 50ms | 19ms | -31ms | -61.59
| getTeamMembersForUser | avg | 18ms | 7ms | -11ms | -61.19
| getTeamsForUser | avg | 17ms | 7ms | -10ms | -60.59
| getAllTeams | avg | 17ms | 7ms | -10ms | -58.29
| getThreadsForUser | avg | 9ms | 4ms | -5ms | -58.16
| getUser | avg | 19ms | 8ms | -11ms | -57.96
| getTeamsUnreadForUser | avg | 23ms | 10ms | -13ms | -57.45
| getPreferences | avg | 21ms | 9ms | -12ms | -57.04
| getPostsForChannelAroundLastUnread | avg | 79ms | 35ms | -44ms | -55.46
| deletePost | avg | 52ms | 26ms | -26ms | -50.47
| upsertDraft | avg | 4ms | 2ms | -2ms | -50.08
| getUsers | avg | 12ms | 7ms | -5ms | -43.38
| saveReaction | avg | 19ms | 11ms | -8ms | -43.24
| getChannelMembersForTeamForUser | avg | 9ms | 5ms | -4ms | -43.00
| getPostsForChannel | avg | 42ms | 25ms | -17ms | -40.62
| getChannelsForTeamForUser | avg | 10ms | 6ms | -4ms | -39.11
| getUsersByNames | avg | 5ms | 3ms | -2ms | -37.01
| getChannelMember | avg | 21ms | 14ms | -7ms | -33.23
| searchGroupChannels | avg | 6ms | 4ms | -2ms | -31.20
| viewChannel | avg | 16ms | 11ms | -5ms | -31.16
| getPublicChannelsForTeam | avg | 19ms | 14ms | -5ms | -25.85
| getClientConfig | avg | 8ms | 6ms | -2ms | -25.49
| getPostThread | avg | 17ms | 13ms | -4ms | -23.14
| getChannelStats | avg | 20ms | 16ms | -4ms | -20.12
| updateReadStateThreadByUser | avg | 31ms | 25ms | -6ms | -19.12
| login | avg | 99ms | 84ms | -15ms | -15.15
| addTeamMember | avg | 1.515s | 1.34s | -175ms | -11.55
| logout | avg | 39ms | 35ms | -4ms | -10.20
| createPost | avg | 433ms | 394ms | -39ms | -9.01
| autocompleteChannelsForTeamForSearch | avg | 137ms | 126ms | -11ms | -8.05
| searchAllChannels | avg | 1.6s | 1.477s | -123ms | -7.69
| getProfileImage | avg | 93ms | 86ms | -7ms | -7.49
| getFileThumbnail | avg | 35ms | 33ms | -2ms | -5.79
| searchUsers | avg | 97ms | 92ms | -5ms | -5.15
| getFilePreview | avg | 44ms | 42ms | -2ms | -4.60
| uploadFileStream | avg | 399ms | 393ms | -6ms | -1.50
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| searchFiles | p99 | 25ms | 0s | -25ms | -100.60
| disablePlugin | p99 | 249ms | 0s | -249ms | -100.15
| getChannelUnread | p99 | 202ms | 5ms | -197ms | -97.52
| patchPost | p99 | 10s | 431ms | -9.569s | -95.69
| setPostReminder | p99 | 487ms | 25ms | -462ms | -94.77
| getChannel | p99 | 379ms | 24ms | -355ms | -93.73
| logout | p99 | 224ms | 50ms | -174ms | -77.51
| getPostThread | p99 | 290ms | 89ms | -201ms | -69.31
| getPostsForChannel | p99 | 773ms | 243ms | -530ms | -68.59
| getUsersByNames | p99 | 122ms | 40ms | -82ms | -67.38
| updateReadStateThreadByUser | p99 | 482ms | 163ms | -319ms | -66.14
| createGroupChannel | p99 | 2.11s | 725ms | -1.385s | -65.64
| getThreadsForUser | p99 | 192ms | 70ms | -122ms | -63.48
| viewChannel | p99 | 264ms | 98ms | -166ms | -62.81
| getChannelMembersForTeamForUser | p99 | 203ms | 77ms | -126ms | -62.18
| getCategoriesForTeamForUser | p99 | 632ms | 249ms | -383ms | -60.59
| saveReaction | p99 | 442ms | 180ms | -262ms | -59.32
| getUsers | p99 | 194ms | 82ms | -112ms | -57.84
| getTeamsUnreadForUser | p99 | 377ms | 163ms | -214ms | -56.80
| getTeamMembersForUser | p99 | 244ms | 106ms | -138ms | -56.67
| getChannelsForTeamForUser | p99 | 222ms | 99ms | -123ms | -55.51
| getPostsForChannelAroundLastUnread | p99 | 929ms | 416ms | -513ms | -55.23
| getTeamsForUser | p99 | 234ms | 113ms | -121ms | -51.75
| getAllTeams | p99 | 236ms | 114ms | -122ms | -51.59
| upsertDraft | p99 | 10ms | 5ms | -5ms | -51.02
| getUser | p99 | 243ms | 120ms | -123ms | -50.71
| searchGroupChannels | p99 | 172ms | 85ms | -87ms | -50.54
| deletePost | p99 | 475ms | 235ms | -240ms | -50.53
| getClientConfig | p99 | 132ms | 69ms | -63ms | -47.60
| autocompleteChannelsForTeamForSearch | p99 | 1.436s | 770ms | -666ms | -46.37
| createDirectChannel | p99 | 903ms | 493ms | -410ms | -45.40
| login | p99 | 874ms | 488ms | -386ms | -44.15
| getPreferences | p99 | 248ms | 161ms | -87ms | -35.15
| getChannelsForUser | p99 | 282ms | 185ms | -97ms | -34.41
| searchAllChannels | p99 | 7.504s | 4.936s | -2.568s | -34.22
| getChannelMember | p99 | 314ms | 209ms | -105ms | -33.44
| addChannelMember | p99 | 1.255s | 873ms | -382ms | -30.44
| autocompleteUsers | p99 | 800ms | 565ms | -235ms | -29.39
| getFileThumbnail | p99 | 135ms | 96ms | -39ms | -28.85
| getPublicChannelsForTeam | p99 | 147ms | 112ms | -35ms | -23.75
| getChannelStats | p99 | 494ms | 387ms | -107ms | -21.65
| createUser | p99 | 603ms | 481ms | -122ms | -20.23
| searchUsers | p99 | 452ms | 366ms | -86ms | -19.02
| addTeamMember | p99 | 5.638s | 4.687s | -951ms | -16.87
| getFilePreview | p99 | 203ms | 175ms | -28ms | -13.81
| createPost | p99 | 2.476s | 2.244s | -232ms | -9.37
| getProfileImage | p99 | 451ms | 439ms | -12ms | -2.66
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.Save |  Avg| 17ms| 0s | -17ms | -102.538
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 280ms| 279ms | -1ms | -0.357
| |  P99| 498ms| 497ms | -1ms | -0.201
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.259
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 5ms | 1ms | 26.380
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelStore.Autocomplete |  Avg| 1.6s| 1.476s | -124ms | -7.751
| |  P99| 7.504s| 4.935s | -2.569s | -34.237
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 137ms| 126ms | -11ms | -8.050
| |  P99| 1.436s| 770ms | -666ms | -46.366
| ChannelStore.CreateDirectChannel |  Avg| 39ms| 17ms | -22ms | -56.451
| |  P99| 740ms| 70ms | -670ms | -90.540
| ChannelStore.CreateInitialSidebarCategories |  Avg| 28ms| 20ms | -8ms | -28.354
| |  P99| 238ms| 177ms | -61ms | -25.638
| ChannelStore.Get |  Avg| 12ms| 4ms | -8ms | -65.391
| |  P99| 225ms| 81ms | -144ms | -63.933
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 16ms| 12ms | -4ms | -25.093
| |  P99| 196ms| 42ms | -154ms | -78.571
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 9ms | -4ms | -31.104
| |  P99| 165ms| 47ms | -118ms | -71.350
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 14ms | -4ms | -22.745
| |  P99| 99ms| 93ms | -6ms | -6.085
| ChannelStore.GetByName |  Avg| 14ms| 7ms | -7ms | -50.307
| |  P99| 219ms| 96ms | -123ms | -56.202
| ChannelStore.GetChannelUnread |  Avg| 5ms| 2ms | -3ms | -59.562
| |  P99| 202ms| 5ms | -197ms | -97.525
| ChannelStore.GetChannels |  Avg| 9ms| 4ms | -5ms | -56.788
| |  P99| 198ms| 77ms | -121ms | -60.990
| ChannelStore.GetChannelsByUser |  Avg| 46ms| 12ms | -34ms | -73.224
| |  P99| 276ms| 164ms | -112ms | -40.543
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 5ms| 3ms | -2ms | -36.871
| |  P99| 142ms| 40ms | -102ms | -71.875
| ChannelStore.GetFileCount |  Avg| 8ms| 5ms | -3ms | -36.845
| |  P99| 174ms| 47ms | -127ms | -73.033
| ChannelStore.GetGuestCount |  Avg| 21ms| 8ms | -13ms | -62.713
| |  P99| 244ms| 141ms | -103ms | -42.153
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 186ms| 158ms | -28ms | -15.087
| |  P99| 926ms| 668ms | -258ms | -27.857
| ChannelStore.GetMemberForPost |  Avg| 5ms| 3ms | -2ms | -43.690
| |  P99| 96ms| 40ms | -56ms | -58.446
| ChannelStore.GetMemberLastViewedAt |  Avg| 14ms| 5ms | -9ms | -63.399
| |  P99| 225ms| 85ms | -140ms | -62.254
| ChannelStore.GetMembersForUser |  Avg| 9ms| 4ms | -5ms | -56.995
| |  P99| 194ms| 69ms | -125ms | -64.370
| ChannelStore.GetMembersForUserWithPagination |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 6ms| 3ms | -3ms | -47.675
| |  P99| 201ms| 32ms | -169ms | -84.184
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 12ms | -6ms | -33.090
| |  P99| 147ms| 77ms | -70ms | -47.507
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 50ms| 19ms | -31ms | -61.894
| |  P99| 627ms| 249ms | -378ms | -60.293
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 33ms| 37ms | 4ms | 12.105
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.486
| ChannelStore.Save |  Avg| 18ms| 11ms | -7ms | -39.904
| |  P99| 204ms| 48ms | -156ms | -76.377
| ChannelStore.SaveMember |  Avg| 80ms| 44ms | -36ms | -45.091
| |  P99| 854ms| 382ms | -472ms | -55.300
| ChannelStore.SearchGroupChannels |  Avg| 6ms| 4ms | -2ms | -31.508
| |  P99| 172ms| 85ms | -87ms | -50.535
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 23ms| 28ms | 5ms | 21.542
| |  P99| 49ms| 93ms | 44ms | 88.939
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 12ms | -16ms | -57.658
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 2ms| 3ms | 1ms | 49.856
| |  P99| 5ms| 7ms | 2ms | 40.404
| DraftStore.Delete |  Avg| 1ms| 2ms | 1ms | 92.623
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 2ms | 1ms | 83.867
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -39.891
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 5ms| 3ms | -2ms | -36.845
| |  P99| 144ms| 49ms | -95ms | -65.931
| EmojiStore.GetMultipleByName |  Avg| 1ms| 2ms | 1ms | 71.634
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 1ms| 0s | -1ms | -87.663
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.161
| FileInfoStore.Get |  Avg| 3ms| 2ms | -1ms | -31.632
| |  P99| 55ms| 9ms | -46ms | -84.194
| FileInfoStore.GetByIds |  Avg| 5ms| 0s | -5ms | -103.888
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.GetForPost |  Avg| 4ms| 2ms | -2ms | -52.534
| |  P99| 78ms| 9ms | -69ms | -88.599
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 75.287
| FileInfoStore.Search |  Avg| 18ms| 0s | -18ms | -98.523
| |  P99| 25ms| 0s | -25ms | -100.604
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 15ms| 5ms | -10ms | -68.805
| |  P99| 229ms| 88ms | -141ms | -61.662
| GroupStore.GetByName |  Avg| 15ms| 7ms | -8ms | -54.109
| |  P99| 231ms| 100ms | -131ms | -56.671
| GroupStore.GetGroups |  Avg| 8ms| 4ms | -4ms | -50.575
| |  P99| 193ms| 65ms | -128ms | -66.212
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 1ms | -1ms | -51.791
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 9ms| 2ms | -7ms | -78.407
| |  P99| 295ms| 28ms | -267ms | -90.524
| JobStore.GetAllByStatus |  Avg| 7ms| 3ms | -4ms | -57.506
| |  P99| 190ms| 60ms | -130ms | -68.377
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 5ms| 3ms | -2ms | -37.005
| |  P99| 102ms| 23ms | -79ms | -77.833
| JobStore.GetNewestJobByStatusesAndType |  Avg| 9ms| 7ms | -2ms | -22.578
| |  P99| 217ms| 194ms | -23ms | -10.599
| JobStore.Save |  Avg| 2ms| 4ms | 2ms | 86.536
| |  P99| 5ms| 19ms | 14ms | 282.828
| JobStore.UpdateOptimistically |  Avg| 2ms| 3ms | 1ms | 41.199
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 2ms | -1ms | -34.472
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -75.484
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 5ms| 2ms | -3ms | -65.710
| |  P99| 106ms| 23ms | -83ms | -78.413
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.560
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.621
| PluginStore.Get |  Avg| 1ms| 2ms | 1ms | 74.218
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 6ms| 2ms | -4ms | -68.308
| |  P99| 196ms| 20ms | -176ms | -89.796
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.328
| PostAcknowledgementStore.GetForPost |  Avg| 6ms| 4ms | -2ms | -32.045
| |  P99| 154ms| 81ms | -73ms | -47.403
| PostAcknowledgementStore.GetForPosts |  Avg| 8ms| 4ms | -4ms | -51.011
| |  P99| 190ms| 47ms | -143ms | -75.429
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 3ms | -3ms | -51.845
| |  P99| 150ms| 49ms | -101ms | -67.121
| PostPriorityStore.GetForPost |  Avg| 6ms| 4ms | -2ms | -33.391
| |  P99| 154ms| 62ms | -92ms | -59.740
| PostPriorityStore.GetForPosts |  Avg| 8ms| 4ms | -4ms | -51.013
| |  P99| 194ms| 52ms | -142ms | -73.308
| PostStore.Delete |  Avg| 15ms| 16ms | 1ms | 6.528
| |  P99| 95ms| 95ms | 0s | 0.000
| PostStore.Get |  Avg| 8ms| 5ms | -3ms | -37.016
| |  P99| 168ms| 60ms | -108ms | -64.241
| PostStore.GetEtag |  Avg| 12ms| 6ms | -6ms | -50.907
| |  P99| 223ms| 98ms | -125ms | -56.099
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.806
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 5ms| 2ms | -3ms | -60.552
| |  P99| 47ms| 5ms | -42ms | -88.889
| PostStore.GetPostReminders |  Avg| 3ms| 6ms | 3ms | 86.714
| |  P99| 10ms| 22ms | 12ms | 123.499
| PostStore.GetPosts |  Avg| 17ms| 8ms | -9ms | -51.734
| |  P99| 228ms| 91ms | -137ms | -60.013
| PostStore.GetPostsAfter |  Avg| 8ms| 3ms | -5ms | -59.912
| |  P99| 205ms| 5ms | -200ms | -97.562
| PostStore.GetPostsBefore |  Avg| 7ms| 5ms | -2ms | -26.809
| |  P99| 165ms| 53ms | -112ms | -68.025
| PostStore.GetPostsByThread |  Avg| 3ms| 2ms | -1ms | -34.729
| |  P99| 40ms| 10ms | -30ms | -74.858
| PostStore.GetPostsSince |  Avg| 12ms| 10ms | -2ms | -16.554
| |  P99| 172ms| 83ms | -89ms | -51.895
| PostStore.GetSingle |  Avg| 5ms| 3ms | -2ms | -43.007
| |  P99| 100ms| 21ms | -79ms | -79.003
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.216
| PostStore.SearchPostsForUser |  Avg| 43ms| 55ms | 12ms | 28.093
| |  P99| 241ms| 250ms | 9ms | 3.732
| PostStore.SetPostReminder |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 141.176
| PostStore.Update |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 51ms| 25ms | -26ms | -50.980
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 5ms| 3ms | -2ms | -37.239
| |  P99| 137ms| 42ms | -95ms | -69.323
| PreferenceStore.GetAll |  Avg| 20ms| 9ms | -11ms | -53.850
| |  P99| 245ms| 159ms | -86ms | -35.162
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.162
| ProductNoticesStore.View |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 120ms| 153ms | 33ms | 27.463
| ReactionStore.GetForPost |  Avg| 6ms| 4ms | -2ms | -33.563
| |  P99| 96ms| 25ms | -71ms | -74.173
| RetentionPolicyStore.GetAll |  Avg| 1ms| 6ms | 5ms | 567.422
| |  P99| 5ms| 25ms | 20ms | 404.040
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 8ms | -11ms | -57.860
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 18ms| 9ms | -9ms | -51.352
| |  P99| 232ms| 125ms | -107ms | -46.148
| SessionStore.GetLRUSessions |  Avg| 17ms| 7ms | -10ms | -59.780
| |  P99| 235ms| 135ms | -100ms | -42.494
| SessionStore.GetSessionsExpired |  Avg| 53ms| 8ms | -45ms | -84.630
| |  P99| 487ms| 48ms | -439ms | -90.052
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 4ms| 2ms | -2ms | -47.358
| |  P99| 98ms| 19ms | -79ms | -80.566
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 20ms| 11ms | -9ms | -44.152
| |  P99| 236ms| 121ms | -115ms | -48.797
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 13ms| 6ms | -7ms | -52.262
| |  P99| 224ms| 88ms | -136ms | -60.705
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 8ms | -16ms | -65.979
| StatusStore.SaveOrUpdate |  Avg| 19ms| 26ms | 7ms | 36.690
| |  P99| 232ms| 300ms | 68ms | 29.282
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 6ms | 4ms | 232.075
| |  P99| 5ms| 10ms | 5ms | 101.010
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.243
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 0s | -2ms | -108.596
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 2ms| 0s | -2ms | -132.630
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 6ms| 3ms | -3ms | -53.507
| |  P99| 147ms| 38ms | -109ms | -74.171
| TeamStore.GetActiveMemberCount |  Avg| 152ms| 157ms | 5ms | 3.292
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 16ms| 6ms | -10ms | -63.379
| |  P99| 231ms| 97ms | -134ms | -58.132
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 14ms| 6ms | -8ms | -55.707
| |  P99| 227ms| 90ms | -137ms | -60.427
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 16ms| 7ms | -9ms | -54.775
| |  P99| 234ms| 113ms | -121ms | -51.786
| TeamStore.GetTeamsForUser |  Avg| 16ms| 6ms | -10ms | -62.296
| |  P99| 235ms| 95ms | -140ms | -59.641
| TeamStore.GetTotalMemberCount |  Avg| 117ms| 119ms | 2ms | 1.717
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 108ms| 100ms | -8ms | -7.406
| |  P99| 395ms| 247ms | -148ms | -37.450
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 6ms| 3ms | -3ms | -53.774
| |  P99| 147ms| 40ms | -107ms | -72.979
| ThreadStore.GetTeamsUnreadForUser |  Avg| 15ms| 6ms | -9ms | -60.906
| |  P99| 232ms| 89ms | -143ms | -61.635
| ThreadStore.GetThreadFollowers |  Avg| 6ms| 3ms | -3ms | -48.997
| |  P99| 170ms| 49ms | -121ms | -71.276
| ThreadStore.GetThreadForUser |  Avg| 9ms| 5ms | -4ms | -46.794
| |  P99| 201ms| 44ms | -157ms | -78.086
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 2ms | -1ms | -30.701
| |  P99| 47ms| 20ms | -27ms | -56.885
| ThreadStore.GetThreadsForUser |  Avg| 6ms| 4ms | -2ms | -31.818
| |  P99| 155ms| 50ms | -105ms | -67.650
| ThreadStore.GetTotalThreads |  Avg| 13ms| 5ms | -8ms | -61.028
| |  P99| 221ms| 85ms | -136ms | -61.405
| ThreadStore.GetTotalUnreadMentions |  Avg| 11ms| 5ms | -6ms | -52.353
| |  P99| 211ms| 84ms | -127ms | -60.211
| ThreadStore.GetTotalUnreadThreads |  Avg| 13ms| 5ms | -8ms | -62.452
| |  P99| 217ms| 84ms | -133ms | -61.195
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 13ms| 5ms | -8ms | -59.658
| |  P99| 222ms| 85ms | -137ms | -61.591
| ThreadStore.MaintainMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -78.341
| UserStore.AnalyticsActiveCount |  Avg| 205ms| 217ms | 12ms | 5.844
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 206ms| 200ms | -6ms | -2.916
| |  P99| 879ms| 660ms | -219ms | -24.916
| UserStore.Count |  Avg| 122ms| 114ms | -8ms | -6.556
| |  P99| 438ms| 428ms | -10ms | -2.286
| UserStore.Get |  Avg| 4ms| 3ms | -1ms | -27.255
| |  P99| 80ms| 28ms | -52ms | -65.221
| UserStore.GetAllProfiles |  Avg| 12ms| 7ms | -5ms | -40.426
| |  P99| 190ms| 86ms | -104ms | -54.667
| UserStore.GetAllProfilesInChannel |  Avg| 504ms| 477ms | -27ms | -5.360
| |  P99| 2.351s| 2.155s | -196ms | -8.336
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 30ms | 6ms | 24.742
| UserStore.GetForLogin |  Avg| 16ms| 8ms | -8ms | -49.192
| |  P99| 235ms| 137ms | -98ms | -41.678
| UserStore.GetMany |  Avg| 31ms| 2ms | -29ms | -93.010
| |  P99| 244ms| 5ms | -239ms | -97.951
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -18.557
| UserStore.GetProfilesByUsernames |  Avg| 5ms| 3ms | -2ms | -38.012
| |  P99| 121ms| 40ms | -81ms | -66.671
| UserStore.GetProfilesInChannel |  Avg| 3ms| 2ms | -1ms | -36.725
| |  P99| 9ms| 5ms | -4ms | -44.199
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 6ms| 3ms | -3ms | -47.576
| |  P99| 141ms| 24ms | -117ms | -83.213
| UserStore.IsEmpty |  Avg| 10ms| 4ms | -6ms | -59.800
| |  P99| 191ms| 75ms | -116ms | -60.574
| UserStore.Save |  Avg| 71ms| 71ms | 0s | 0.000
| |  P99| 186ms| 187ms | 1ms | 0.537
| UserStore.Search |  Avg| 95ms| 91ms | -4ms | -4.214
| |  P99| 443ms| 368ms | -75ms | -16.932
| UserStore.Update |  Avg| 4ms| 5ms | 1ms | 22.471
| |  P99| 21ms| 22ms | 1ms | 4.842
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.776
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.271
| UserTermsOfServiceStore.GetByUser |  Avg| 17ms| 7ms | -10ms | -60.054
| |  P99| 234ms| 117ms | -117ms | -50.053
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 5ms | -2ms | -28.181
| |  P99| 135ms| 45ms | -90ms | -66.859
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 195ms| 227ms | 32ms | 16.391
| | P99| 1.255s| 873ms | -382ms | -30.437
| addTeamMember | Avg| 1.515s| 1.34s | -175ms | -11.555
| | P99| 5.638s| 4.687s | -951ms | -16.868
| autocompleteChannelsForTeamForSearch | Avg| 137ms| 126ms | -11ms | -8.047
| | P99| 1.436s| 770ms | -666ms | -46.366
| autocompleteEmojis | Avg| 1ms| 0s | -1ms | -83.685
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 166ms| 172ms | 6ms | 3.617
| | P99| 800ms| 565ms | -235ms | -29.387
| createChannel | Avg| 217ms| 283ms | 66ms | 30.414
| | P99| 249ms| 496ms | 247ms | 99.396
| createDirectChannel | Avg| 201ms| 242ms | 41ms | 20.349
| | P99| 903ms| 493ms | -410ms | -45.404
| createGroupChannel | Avg| 328ms| 342ms | 14ms | 4.275
| | P99| 2.11s| 725ms | -1.385s | -65.640
| createPost | Avg| 433ms| 394ms | -39ms | -9.011
| | P99| 2.476s| 2.244s | -232ms | -9.371
| createUser | Avg| 136ms| 139ms | 3ms | 2.206
| | P99| 603ms| 481ms | -122ms | -20.226
| deleteDraft | Avg| 2ms| 3ms | 1ms | 50.920
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 52ms| 26ms | -26ms | -50.469
| | P99| 475ms| 235ms | -240ms | -50.527
| disablePlugin | Avg| 235ms| 0s | -235ms | -99.841
| | P99| 249ms| 0s | -249ms | -100.148
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 17ms| 7ms | -10ms | -58.287
| | P99| 236ms| 114ms | -122ms | -51.590
| getAnalytics | Avg| 204ms| 230ms | 26ms | 12.737
| | P99| 493ms| 492ms | -1ms | -0.203
| getCategoriesForTeamForUser | Avg| 50ms| 19ms | -31ms | -61.591
| | P99| 632ms| 249ms | -383ms | -60.590
| getChannel | Avg| 18ms| 6ms | -12ms | -68.157
| | P99| 379ms| 24ms | -355ms | -93.729
| getChannelMember | Avg| 21ms| 14ms | -7ms | -33.225
| | P99| 314ms| 209ms | -105ms | -33.435
| getChannelMembersForTeamForUser | Avg| 9ms| 5ms | -4ms | -42.997
| | P99| 203ms| 77ms | -126ms | -62.181
| getChannelStats | Avg| 20ms| 16ms | -4ms | -20.120
| | P99| 494ms| 387ms | -107ms | -21.646
| getChannelUnread | Avg| 6ms| 2ms | -4ms | -68.464
| | P99| 202ms| 5ms | -197ms | -97.525
| getChannelsForTeamForUser | Avg| 10ms| 6ms | -4ms | -39.109
| | P99| 222ms| 99ms | -123ms | -55.514
| getChannelsForUser | Avg| 48ms| 13ms | -35ms | -73.442
| | P99| 282ms| 185ms | -97ms | -34.412
| getClientConfig | Avg| 8ms| 6ms | -2ms | -25.489
| | P99| 132ms| 69ms | -63ms | -47.604
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 0s | -3ms | -116.630
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 44ms| 42ms | -2ms | -4.595
| | P99| 203ms| 175ms | -28ms | -13.805
| getFileThumbnail | Avg| 35ms| 33ms | -2ms | -5.793
| | P99| 135ms| 96ms | -39ms | -28.849
| getFilteredUsersStats | Avg| 70ms| 70ms | 0s | 0.000
| | P99| 247ms| 247ms | 0s | 0.000
| getGroups | Avg| 3ms| 2ms | -1ms | -39.221
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 1ms | -1ms | -63.434
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 17ms| 13ms | -4ms | -23.141
| | P99| 290ms| 89ms | -201ms | -69.310
| getPostsForChannel | Avg| 42ms| 25ms | -17ms | -40.618
| | P99| 773ms| 243ms | -530ms | -68.592
| getPostsForChannelAroundLastUnread | Avg| 79ms| 35ms | -44ms | -55.462
| | P99| 929ms| 416ms | -513ms | -55.232
| getPreferences | Avg| 21ms| 9ms | -12ms | -57.036
| | P99| 248ms| 161ms | -87ms | -35.149
| getPrevTrialLicense | Avg| 2ms| 1ms | -1ms | -61.314
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 93ms| 86ms | -7ms | -7.495
| | P99| 451ms| 439ms | -12ms | -2.661
| getPublicChannelsForTeam | Avg| 19ms| 14ms | -5ms | -25.848
| | P99| 147ms| 112ms | -35ms | -23.754
| getRolesByNames | Avg| 4ms| 1ms | -3ms | -68.574
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 13.072
| getTeamMembersForUser | Avg| 18ms| 7ms | -11ms | -61.190
| | P99| 244ms| 106ms | -138ms | -56.667
| getTeamStats | Avg| 153ms| 159ms | 6ms | 3.932
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 17ms| 7ms | -10ms | -60.587
| | P99| 234ms| 113ms | -121ms | -51.749
| getTeamsUnreadForUser | Avg| 23ms| 10ms | -13ms | -57.445
| | P99| 377ms| 163ms | -214ms | -56.796
| getThreadsForUser | Avg| 9ms| 4ms | -5ms | -58.164
| | P99| 192ms| 70ms | -122ms | -63.483
| getUser | Avg| 19ms| 8ms | -11ms | -57.964
| | P99| 243ms| 120ms | -123ms | -50.713
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 12ms| 7ms | -5ms | -43.376
| | P99| 194ms| 82ms | -112ms | -57.843
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 5ms| 3ms | -2ms | -37.011
| | P99| 122ms| 40ms | -82ms | -67.384
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 99ms| 84ms | -15ms | -15.151
| | P99| 874ms| 488ms | -386ms | -44.151
| logout | Avg| 39ms| 35ms | -4ms | -10.201
| | P99| 224ms| 50ms | -174ms | -77.508
| patchPost | Avg| 2.379s| 41ms | -2.338s | -98.279
| | P99| 10s| 431ms | -9.569s | -95.690
| removeUserCustomStatus | Avg| 125ms| 140ms | 15ms | 12.024
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 19ms| 11ms | -8ms | -43.241
| | P99| 442ms| 180ms | -262ms | -59.325
| searchAllChannels | Avg| 1.6s| 1.477s | -123ms | -7.688
| | P99| 7.504s| 4.936s | -2.568s | -34.224
| searchFiles | Avg| 21ms| 0s | -21ms | -101.982
| | P99| 25ms| 0s | -25ms | -100.604
| searchGroupChannels | Avg| 6ms| 4ms | -2ms | -31.204
| | P99| 172ms| 85ms | -87ms | -50.535
| searchPostsInTeam | Avg| 54ms| 62ms | 8ms | 14.856
| | P99| 450ms| 485ms | 35ms | 7.786
| searchUsers | Avg| 97ms| 92ms | -5ms | -5.153
| | P99| 452ms| 366ms | -86ms | -19.015
| setPostReminder | Avg| 84ms| 15ms | -69ms | -81.851
| | P99| 487ms| 25ms | -462ms | -94.769
| unfollowThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 33ms| 38ms | 5ms | 15.318
| | P99| 95ms| 97ms | 2ms | 2.100
| updatePreferences | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 31ms| 25ms | -6ms | -19.121
| | P99| 482ms| 163ms | -319ms | -66.135
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 399ms| 393ms | -6ms | -1.504
| | P99| 990ms| 986ms | -4ms | -0.404
| upsertDraft | Avg| 4ms| 2ms | -2ms | -50.080
| | P99| 10ms| 5ms | -5ms | -51.020
| viewChannel | Avg| 16ms| 11ms | -5ms | -31.162
| | P99| 264ms| 98ms | -166ms | -62.814
